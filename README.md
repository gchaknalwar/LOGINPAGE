# 🔐 Login & Signup Application (MERN Stack)

A simple **Login & Signup authentication application** built using the **MERN Technology Stack**. This project demonstrates how frontend and backend work together to handle user authentication securely.

---

## 🚀 Tech Stack Used

### 🌐 Frontend

* **React.js** – UI development
* **JavaScript (ES6+)** – Logic & interactions
* **HTML5** – Structure
* **CSS3** – Styling
* **Axios / Fetch API** – API communication

### 🛠 Backend

* **Node.js** – Runtime environment
* **Express.js** – Backend framework
* **MongoDB** – Database
* **Mongoose** – MongoDB ODM
* **bcryptjs** – Password hashing
* **jsonwebtoken (JWT)** – Authentication
* **CORS** – Cross-origin handling
* **dotenv** – Environment variables

---

## ✨ Features

* User Signup (Register)
* User Login (Authentication)
* Password Encryption using bcrypt
* JWT-based authentication
* Form validation (Frontend + Backend)
* Secure API endpoints
* Clean separation of Frontend & Backend

---

## 📂 Project Structure

```
project-root/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Login.jsx
│   │   │   └── Signup.jsx
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── backend/
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   └── authRoutes.js
│   ├── controllers/
│   │   └── authController.js
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## 🔄 Application Flow

1. User enters email & password on **Signup/Login page**
2. Frontend sends data to backend via API
3. Backend validates data
4. Password is encrypted and stored in MongoDB (Signup)
5. On login, credentials are verified
6. JWT token is generated and sent to frontend
7. Frontend uses token for authentication

---

## 🧪 API Endpoints

### Signup

```
POST /api/auth/signup
```

### Login

```
POST /api/auth/login
```

---

## 🖥 How to Run the Project

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔐 Environment Variables (.env)

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 🎯 Purpose of the Project

* Learn **MERN stack authentication flow**
* Understand **controlled forms & API integration**
* Practice **real-world frontend-backend communication**
* Strengthen basics of **Login & Signup systems**

---

## 📌 Future Improvements

* Add email verification
* Forgot password feature
* Role-based authentication
* UI enhancement

---

## 👨‍💻 Author

**Govind Chaknalwar**
Frontend Developer | MERN Stack Learner

---

⭐ If you like this project, give it a star!
