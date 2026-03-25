# T-Codex (PROJ_TRIUMPH)

T-Codex is a full-stack web application featuring a React-based frontend and an Express backend. The project is designed with a focus on cross-platform accessibility and secure data management.

**Deployed URL**: [https://triumphinfo.netlify.app](https://triumphinfo.netlify.app)

## Features
* **Cross-Platform Detection**: Utilizes `react-device-detect` to provide optimized experiences for mobile and desktop users.
* **Secure Authentication**: Backend implementation includes `jsonwebtoken` for secure user sessions.
* **Modern UI Components**: Frontend built with React 19, incorporating `react-toastify` for real-time notifications and `react-router-dom` for seamless navigation.
* **Integrated Development**: Uses Vite for a fast development and build process.

## Project Structure
* **TR_FR**: The React frontend application.
* **TR_BE**: The Node.js/Express backend server.

## Tech Stack

### Frontend
* **Core**: React 19, Vite
* **Routing**: React Router DOM
* **Utilities**: react-device-detect, react-toastify
* **Linting**: ESLint

### Backend
* **Server**: Express
* **Security**: JSON Web Token (JWT), CORS
* **Environment Management**: Dotenv

## Getting Started

### Backend Setup
1. Navigate to the `TR_BE` directory.
2. Install dependencies:
   ```bash
   npm install
