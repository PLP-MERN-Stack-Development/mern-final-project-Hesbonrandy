# MERN Stack Capstone Project

A full-stack MERN (MongoDB, Express, React, Node) capstone application demonstrating backend APIs, a responsive React frontend, authentication, data persistence, testing, and deployment.

## Features
- User authentication (signup, login, JWT)
- CRUD operations with MongoDB
- Responsive React UI with routing and form validation
- Unit and integration tests for backend and frontend
- Deployed production build

## Setup (Local)

Prerequisites:
- Node.js v18+ and npm
- Git
- MongoDB (local or Atlas)

Steps:
1. Clone the repo
   - Open PowerShell and run:
     git clone <your-repo-url>
     cd mern-final-project-Hesbonrandy
2. Install dependencies (root, server, client as applicable)
   - From repo root:
     npm install
   - If separate server/client folders:
     cd server && npm install
     cd ../client && npm install
3. Environment
   - Create a .env file in the server folder with required variables (example):
     MONGO_URI=<your-mongo-uri>
     JWT_SECRET=<your-jwt-secret>
     PORT=5000
4. Run locally
   - For combined start (adjust commands to your repo scripts):
     npm run dev
   - Or run server and client in separate terminals:
     cd server && npm run dev
     cd client && npm start
5. Run tests
   - npm test (or follow server/client test scripts)

## Deployed Application
Live demo: https://your-deployed-app.example.com
(Replace with your actual deployment URL)

## Demo Video (5–10 min)
Watch the walkthrough: https://youtu.be/your-demo-video
(Replace with your recorded 5–10 minute demo link)

## Screenshots
Place screenshots in ./docs/screenshots and reference them here.

![Home Page](./docs/screenshots/home.png)
![Create Item](./docs/screenshots/create-item.png)
![User Profile](./docs/screenshots/profile.png)

## Project Structure (overview)
- /server — Express API, routes, models
- /client — React app (components, pages, services)
- /tests — unit/integration tests
- /docs/screenshots — images used in README

## Technologies
- React, React Router, Redux (optional)
- Node.js, Express
- MongoDB (Mongoose)
- JWT for authentication
- Jest, Supertest, React Testing Library

## Deployment
- Example hosts: Vercel/Netlify (frontend), Render/Heroku (backend), MongoDB Atlas
- Ensure CORS and environment variables are configured for production.

## Screenshots & Assets
1. Create a folder: ./docs/screenshots
2. Add PNGs (home.png, create-item.png, profile.png)
3. Commit them and update the image paths above if needed.

## License
Specify your license (e.g., MIT). Replace or remove if not applicable.

## Commit & Push (example)
Open PowerShell in the repo root:
git add README.md docs/screenshots/*
git commit -m "docs: update README with description, setup, demo and screenshots"
git push