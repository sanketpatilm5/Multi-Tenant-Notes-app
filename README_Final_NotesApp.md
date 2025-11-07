# 📝 Multi-Tenant Notes App (Backend Developer Intern Assignment)

This project is a **secure, scalable full-stack Notes Application** built for the **Backend Developer Internship Assignment**.  
It demonstrates **JWT authentication**, **role-based access**, and **CRUD APIs** with a working UI for testing.

---

## 🚀 Features Implemented

### 🧠 Core Backend Features
✅ User registration & login with **bcrypt password hashing**  
✅ **JWT authentication** (token-based access)  
✅ **Role-based access control** (Admin & User)  
✅ **CRUD APIs** for Notes (Create, Read, Update, Delete)  
✅ **Input validation** & structured error handling  
✅ **API versioning** (e.g., `/api/v1/notes`)  
✅ **Scalable folder structure** for future modules  
✅ **MongoDB/Postgres ready** (via environment config)

---

### 🧩 Frontend Features
✅ Simple responsive UI to:
- Register and log in users  
- Access a protected dashboard using JWT  
- Perform CRUD on notes  
- Display success/error messages from APIs  

Built with **React.js / Vanilla JS** and directly connected to backend APIs.

---

## 🧱 Tech Stack

| Layer | Tech |
|-------|------|
| Backend | Node.js, Express.js |
| Authentication | JWT, bcrypt |
| Database | MongoDB / PostgreSQL (via .env config) |
| Frontend | React.js / Vanilla JS |
| Docs | Postman Collection / Swagger |
| Deployment Ready | Render (backend) + Netlify (frontend) |

---

## ⚙️ Local Setup Guide

### 1️⃣ Clone or Extract the Project
```bash
cd Notes-App
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Configure Environment Variables  
Create a `.env` file in the root folder:

```env
PORT=5000
MONGO_URI=your_database_connection_string
JWT_SECRET=yourSuperSecretKey123
```

If using PostgreSQL (e.g. Neon), use:
```env
DATABASE_URL=your_neon_postgres_url
```

---

### 4️⃣ Run the Project
```bash
npm start
```

OR if using nodemon:
```bash
npm run dev
```

✅ Server will start at **http://localhost:5000**

---

### 5️⃣ Access the Frontend
Open **index.html** (or React build folder) and interact with the UI:
- Register / Login  
- Manage notes  
- Observe live API interactions  

---

## 🔒 Security Implementations

- All passwords are **hashed** using bcrypt.  
- Tokens are **signed with JWT secret** and verified for each request.  
- Input is sanitized and validated before DB operations.  
- API follows REST best practices & HTTP status codes.

---

## 🧠 Scalability Notes

This backend can scale easily by:
- Deploying microservices for auth, notes, and users
- Adding Redis caching for frequent queries
- Using Nginx load balancing or AWS ALB
- Migrating to Docker for containerized deployments

---

## 📘 API Documentation

A full **Postman Collection** is included (`/docs/postman_collection.json`)  
Example Endpoints:

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/api/v1/auth/register` | Register a new user |
| POST | `/api/v1/auth/login` | Login and get JWT |
| GET | `/api/v1/notes` | Get all notes |
| POST | `/api/v1/notes` | Create a note |
| PUT | `/api/v1/notes/:id` | Update note |
| DELETE | `/api/v1/notes/:id` | Delete note |

---

## 🧩 Folder Structure

```
Notes-App/
│
├── src/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── index.js / server.js
│
├── public/ (Frontend)
├── package.json
└── README.md
```

---

## 📨 Submission Information

**Candidate:** Sanket Vasant Patil  
**Role:** Backend Developer Intern  
**Email:** sanketpatil@example.com  
**Location:** Mumbai, India  

To run locally, simply install dependencies, configure `.env`, and start the server.  
Both backend and frontend are included in the same folder for simplicity.

---

### 📧 Contact for Verification

If any issues arise while testing, please reach out:
```
saami@bajarangs.com  
nagasai@bajarangs.com  
chetan@bajarangs.com  
CC: sonika@primetrade.ai
```

---

**Made with ❤️ by Sanket Vasant Patil**
