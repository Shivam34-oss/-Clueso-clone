# Clueso Clone – Full Stack Assignment

This is a Clueso-inspired full stack web application built as part of a technical assignment.  
The focus of this project is **product thinking, clean architecture, and realistic UX**, rather than real AI integrations.

---

## 🚀 Features

### 🔐 Authentication
- User Signup & Login
- Password hashing using bcrypt
- JWT-based authentication
- Protected routes (Dashboard access only after login)

### 📊 Dashboard
- Clean dashboard UI after login
- Navbar with Dashboard, Create Guide, Logout
- Authentication-aware navigation

### 🤖 AI Insight Simulation
- "Generate AI Insight" feature
- Simulated AI processing delay (2–5 seconds)
- Loader state for realistic UX
- Generated insights stored in MongoDB
- Insight history visible on dashboard

> Note: AI is simulated to demonstrate async workflows and UX, not external AI APIs.

### 📝 Guide Creation Flow
- Create guide page similar to Clueso workflow
- Backend API to store guides
- Clean and simple content creation UX

### 🗄️ Robust Backend Architecture
- MVC folder structure
- Controllers, routes, models separated
- MongoDB for persistent storage
- Middleware for auth protection

---

## 🧱 Tech Stack

**Frontend**
- React (Vite)
- React Router
- Axios
- Bootstrap

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT
- bcrypt

---

## 📁 Project Structure

clueso-clone/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ └── main.jsx
│ └── vite.config.js
└── README.md

## ▶️ How to Run Locally

### Backend
```bash
cd backend
npm install
node server.js