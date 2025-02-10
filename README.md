# Gitify -> Know Your Code Better

[![Next.js](https://img.shields.io/badge/Next.js-15-blue?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Prisma](https://img.shields.io/badge/Prisma-6.2-orange?logo=prisma)](https://www.prisma.io/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-blueviolet?logo=tailwind-css)](https://tailwindcss.com/)

A modern Git management platform that allows users to log in via Git providers, manage repositories, and configure custom settings like "Auto Review."



https://github.com/user-attachments/assets/0976e1aa-3735-4981-b19f-4c124ea264ff



## ✨ Features

- **Multi-Provider Authentication**: Log in with GitHub, GitLab, or Bitbucket.
- **Repository Management**: View and manage your repositories with an "Auto Review" toggle.
- **Repository Statistics**: View stars count, default branch name, and auto-review status.
- **Profile Page**: Display user information, including the total number of repositories and those with auto-review enabled.
- **Logout Functionality**: Easily log out of the platform.

## 🛠️ Tech Stack

**Backend**  
- Express.js
- MongoDB  
- Zod

**Frontend**  
- Next.js 13  
- React 18  
- React Table  
- shadcn/ui  
- Tailwind CSS  

## 🚀 Installation

### Docker Installation (Alternative Method)

1. Clone the repository
   ```bash
   git clone https://github.com/sid0000007/Gitify.git
   cd gitify

3. Set up environment variables (Root Directory)
  
   ```bash
    MONGODB_URI=your-mongodb-uri
    JWT_SECRET=your-secret-key
    GITHUB_CLIENT_ID=your-github-client-id
    GITHUB_CLIENT_SECRET=your-github-client-secret
    GITLAB_CLIENT_ID=your-gitlab-client-id
    GITLAB_CLIENT_SECRET=your-gitlab-client-secret
    GITLAB_REDIRECT_URI=http://localhost:3000/api/auth/callback/gitlab
    GITHUB_TOKEN=your-github-token
    GITLAB_TOKEN=your-gitlab-token
    NEXT_PUBLIC_API_URL=http://localhost:3001
    NEXT_PUBLIC_GITHUB_CLIENT_ID=your-github-client-id
    NEXT_PUBLIC_GITLAB_CLIENT_ID=your-gitlab-client-id 

3. Running command (In Root Directory)
   ```bash
   docker-compose up --build

4. Visit http://localhost:3000 to access the application (Client).

5. Visit http://localhost:3001 to access the application (Backend).

### Manual Installation (Alternative Method)

1. Clone the repository
   ```bash
   git clone https://github.com/sid0000007/Gitify.git
   cd gitify
2. Install dependencies
   ```bash
   npm install  

3. Set up environment variables (Backend)
  
   ```bash
    MONGODB_URI=
    JWT_SECRET=
    GITHUB_CLIENT_ID=
    GITHUB_CLIENT_SECRET=
    GITHUB_TOKEN=
    GITLAB_CLIENT_ID=    

    PORT=3001
    GITLAB_CLIENT_ID=
    GITLAB_CLIENT_SECRET=
    GITLAB_REDIRECT_URI=http://localhost:3000/api/auth/callback/gitlab   


4. Set up environment variables (Frontned)

   ```bash
    NEXT_PUBLIC_API_URL=http://localhost:3001
    NEXT_PUBLIC_GITHUB_CLIENT_ID=
    NEXT_PUBLIC_GITLAB_CLIENT_ID=

5. Running command (In both Backend and frontend Directory)
   ```bash
   npm run dev
6. Visit http://localhost:3000 to access the application.

📂 Project Structure
--------------------


<img width="279" alt="Screenshot 2025-02-09 at 1 50 21 PM" src="https://github.com/user-attachments/assets/012cd0a4-d6a5-4628-902c-620426174c45" />


  
## Key Implementation Details
Multi-Provider Authentication: Integrated OAuth for GitHub and GitLab.

Repository List & Config: Display repositories with an "Auto Review" toggle.

Repository Statistics: Show stars count, default branch name, and auto-review status.

Profile Page: Display user information and repository counts.

REST API: All screens are powered by RESTful APIs.

Code Quality: Reviewed using PantoMaxBot.

## 📝 Additional Requirements
Code Quality: Ensure high code quality and adhere to best practices.

PR Process: Commit changes to a feature-1 branch and create a PR to the main branch.

PantoMaxBot: Install and use PantoMaxBot for PR reviews.



   
   
