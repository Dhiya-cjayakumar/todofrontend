# MERN To-Do List App

A full-stack **To-Do List** web application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). This app allows users to register, log in, and manage their tasks with customizable status and priority.


---

## Features

- 🔐 User Authentication (Register & Login with JWT)
- 📝 Add, edit, delete tasks
- 🎯 Mark tasks as **Pending** or **Completed**
- ⚡ Set task **Priority** (Low, Medium, High)
- 🔍 Filter tasks by status and priority
- 💅 Clean and responsive UI
- ☁️ Deployed on [Render](https://render.com)

---

## 🛠️ Tech Stack

| Frontend | Backend | Database | Auth |
|----------|---------|----------|------|
| React.js | Node.js | MongoDB  | JWT  |
| Tailwind CSS | Express.js | Mongoose | bcrypt |

---

## 🔗 Live Demo
[deployed model](https://todofrontend-1qsi.onrender.com)

---


## 🧑‍💻 Local Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   
**Install frontend & backend dependencies**
```bash
  cd frontend
  npm install

  cd ../backend
  npm install
  
**Set up environment variables in backend/.env**
MONGOURL=your_mongodb_connection_string

**Run the backend**
cd backend
npm start

**Run the frontend**
cd frontend
npm start

Folder Structure
```bash
├── frontend/           # React app
│   └── App.js, components, pages...
├── backend/            # Express API
│   └── server.js, models, routes...
└── README.md
```


**Dependencies**


Frontend: React, React Router DOM


Backend: Express, Mongoose, bcryptjs, JWT, dotenv, CORS

---
**Authentication Flow**


Passwords are hashed using bcryptjs


JWT tokens are generated on login and stored in localStorage


Protected routes are guarded using Authorization: Bearer <token>

---
**Author**


Dhiya C Jayakumar


GitHub - https://github.com/Dhiya-cjayakumar


LinkedIn - www.linkedin.com/in/dhiya-cjayakumar

---
**License**


This project is licensed under the MIT License.


