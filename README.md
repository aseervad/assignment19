# 🎯 Assignment 19 – JWT Authentication with Flask + React

This project implements a full-stack **IELTS Speaking and Listening Test Platform** using:

- 🧠 **React + TypeScript** (Frontend)
- 🐍 **Flask (Python)** (Backend)
- 🔐 **JWT Authentication**
- 📦 **SQLite Database**
- 🎙️ **Audio Recording & Upload**

---

## 📌 Features

### ✅ Authentication
- Secure login system using **JSON Web Tokens (JWT)**
- Protected routes for authenticated users
- Role-based access control (`admin` / `test_taker`)

### 🎓 Test Platform
- Speaking Test: Answer questions, record responses, submit answers
- Listening Test: Upload and play audio files, submit answers

### 🛡️ Backend
- Flask REST APIs
- SQLAlchemy ORM for DB operations
- JWT-based route protection
- Modular route structure (`auth_routes.py`, `test_routes.py`, etc.)

### 🎨 Frontend
- Built with **React + TypeScript + Bootstrap**
- Dynamic routing with `react-router-dom`
- Components: `Login`, `AdminDashboard`, `TestTakerDashboard`, `AudioRecorder`, `QuestionCard`, etc.

---

🧪 API Highlights
POST /api/auth/login – Login and receive JWT token

GET /api/speaking-tests – Fetch speaking test data (protected)

POST /api/listening-tests – Upload new listening test

🔐 JWT Token Format
All protected requests must include:

Authorization: Bearer <your_token_here>
🧠 Admin Credentials

Email: admin@gmail.com
Password: Admin@123
Use the above to test admin-specific dashboard functionalities.

🙏 Acknowledgements
This project is part of Edubot PFSD Assignment 19, aimed at mastering authentication and role-based access in full-stack web development.

