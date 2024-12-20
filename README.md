# CodeAnt-AI

This repository contains the frontend code for **CodeAnt AI**, a platform that uses AI to detect and autofix bad code. The application provides users with options to sign in through various platforms and manage their repositories through a clean and intuitive interface.

---

## Features

- AI-powered detection and autofix for bad code.
- Multi-platform sign-in options: GitHub, Bitbucket, Azure DevOps, and GitLab.
- Dashboard for managing repositories, displaying both public and private repositories.
- Statistics on language support, developers, hours saved, and issues fixed.

---

## Installation

Follow these steps to set up the frontend locally:

1. Clone this repository:
   git clone https://github.com/your-repo-link.git

2. Navigate to the project directory:
   cd codeant-ai-frontend

3. Install the required dependencies:
   npm install

4. Start the development server:
   npm start

5. Open the application in your browser at http://localhost:5173.

## Folder Structure

├── public/          # Static assets like index.html and icons
├── src/
│   ├── assets/      # Images and other static files
│   ├── components/  # Reusable React components (e.g., Header, Footer)
│   ├── pages/       # Main application pages (e.g., Dashboard, Login)
│   ├── styles/      # CSS or Tailwind CSS files
│   ├── App.js       # Main React component
│   └── index.js     # Entry point of the application
└── package.json     # Project metadata and dependencies
├── .git/

## Technologies Used

React.js: For building the user interface.
Tailwind CSS: For styling and responsiveness.
npm: For package management.

## Getting Started

To explore the application:

Run the application using npm start.
Sign in using one of the available options (GitHub, Bitbucket, Azure DevOps, GitLab).
Manage your repositories from the dashboard.
