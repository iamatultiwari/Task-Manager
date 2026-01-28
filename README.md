Task Manager (Full Stack)

A simple full-stack Task Manager application built using React (Vite) for the frontend and Node.js + Express for the backend.

This project allows users to:

Add tasks

View tasks

Delete tasks

Data is currently stored in a local JSON file.

🚀 Features

Add new task

Show all tasks

Delete task

React frontend

Node.js + Express REST API

Proper backend folder structure (routes, controllers, models)

JSON file used as database

🛠️ Tech Stack
Frontend

React (Vite)

JavaScript

CSS

Backend

Node.js

Express.js

📁 Project Structure
proj/
│
├── Backend/
│   ├── controllers/
│   │   └── taskControllers.js
│   │
│   ├── data/
│   │   └── tasks.json
│   │
│   ├── models/
│   │   └── taskModel.js
│   │
│   ├── routes/
│   │   └── taskRoutes.js
│   │
│   ├── node_modules/
│   ├── .env
│   ├── .gitignore
│   ├── app.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── node_modules/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   │
│   ├── .gitignore
│   ├── eslint.config.js
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   └── vite.config.js
│
└── README.md


⚙️ How to Run the Project
1️⃣ Start Backend

Open terminal:

cd Backend
npm install
node app.js

2️⃣ Start Frontend

Open another terminal:

cd frontend
npm install
npm run dev

🔗 API Endpoints

GET /tasks → Get all tasks

POST /tasks → Add new task

DELETE /tasks/:id → Delete task

🎯 Purpose of this Project

Practice React + Node integration

Learn REST API development

Understand backend folder structure

Improve full-stack development skills

👨‍💻 Author

Atul Tiwari
GitHub: https://github.com/iamatultiwari


🧠 Thought Process

I first broke the problem into smaller parts to understand the core requirements.

Then I planned the structure and data flow before writing code.

I chose a simple and readable approach to avoid unnecessary complexity.

This made debugging and future changes easier.

⚠️ Challenges Faced

Handling edge cases caused unexpected errors during execution.

Some bugs only appeared at runtime and were hard to trace.

I used logging and step-by-step debugging to fix them.

Refactoring helped keep the code clean and organized.
