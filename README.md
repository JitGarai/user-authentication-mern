# User Authentication Web Application (MERN Stack)

A full-stack user authentication web application built using the MERN stack.  
The application provides secure user registration and login functionality with modern authentication practices.

---

## 🚀 Features

- User Registration & Login
- Secure password hashing using bcrypt
- JWT-based authentication
- Protected routes
- RESTful API architecture
- Responsive UI built with React and Tailwind CSS

---

## 🛠 Tech Stack

**Frontend**
- React.js
- Tailwind CSS
- JavaScript

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB

**Authentication**
- JSON Web Tokens (JWT)
- bcrypt



## 📁 Project Structure
user-authentication-mern/
├── client/ # React frontend
├── server/ # Node.js & Express backend
├── README.md
├── .gitignore

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

git clone https://github.com/your-username/user-authentication-mern.git
cd user-authentication-mern

### 2️⃣ Backend Setup

cd server
npm install

Create a .env file inside server directory:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Run the backend:

npm run dev

### 3️⃣ Frontend Setup

cd client
npm install
npm start

## Authentication Flow

a. User registers with email and password

b. Password is hashed before storing in MongoDB

c. On login, JWT token is generated

d. Token is used to access protected routes

## Future Improvements

a. Email verification

b. Password reset functionality

c. Role-based authentication

d. OAuth (Google Login)

e. Improved UI/UX

## Author

Debabrata Garai
B.Tech Information Technology, IIEST Shibpur