MERN Feedback Management System

A full-stack feedback management application built using the MERN stack (MongoDB, Express.js, React, and Node.js).

Features
Dashboard to view feedback records
Add new feedback
Update existing feedback
Delete feedback
REST API powered by Express.js and Node.js
MongoDB Atlas database integration
Responsive user interface for desktop and mobile devices
Technologies Used

Frontend

React
Vite
CSS

Backend

Node.js
Express.js
MongoDB Atlas
Mongoose
Project Structure
text
mern-student/
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
├── backend/
│   ├── server.js
│   ├── package.json
│   └── .env.example
├── README.md
└── .gitignore

Prerequisites
Node.js and npm
A MongoDB Atlas account or MongoDB database
Git
Installation
1. Clone the repository
bash
git clone https://github.com/snehapramod1/mern-feedback-management.git
cd mern-feedback-management

2. Install frontend dependencies
bash
cd frontend
npm install

3. Configure the backend

Open a separate terminal:

bash
cd backend
npm install


Create a .env file inside the backend directory and configure your MongoDB connection string:

env
MONGODB_URI=your_mongodb_connection_string
PORT=5000


Replace the placeholder with your actual MongoDB connection string. Never commit real credentials to GitHub.

4. Start the backend

From the backend directory, run:

bash
npm start

5. Start the frontend

From the frontend directory, run:

bash
npm run dev


Open the local URL shown in your frontend terminal, usually http://localhost:5173.

Environment Variables
Variable	Description
MONGODB_URI	MongoDB connection string
PORT	Backend server port

Check the backend code for the exact environment variable names and port configuration used in your project.

Usage
Start the backend and frontend.
Open the frontend in your browser.
View feedback on the dashboard.
Add, update, and delete feedback records.
License

This project was created for educational and demonstration purposes.
