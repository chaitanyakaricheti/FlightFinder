# ✈️ Flight Booking App – MERN Stack

![MERN](https://img.shields.io/badge/Stack-MERN-green)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)
![Express](https://img.shields.io/badge/Backend-Express-black)
![React](https://img.shields.io/badge/Frontend-React-blue)
![Node](https://img.shields.io/badge/Runtime-Node.js-green)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

A full-stack **Flight Booking Application** built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).

This project demonstrates:
- Authentication (JWT)
- Role-based access (User/Admin)
- Flight management system
- Booking system
- Secure backend APIs
- Deployment-ready structure
- Docker support

---


# 🚀 Tech Stack

## Frontend
- React.js
- Axios
- React Router DOM
- Bootstrap / CSS

## Backend
- Node.js
- Express.js
- JWT Authentication
- bcrypt (Password Hashing)

## Database
- MongoDB Atlas

---

# 📂 Project Structure

```
Flight-Booking-App/
│
├── client/                 # React Frontend
│   ├── src/
│   └── package.json
│
├── server/                 # Node + Express Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   ├── index.js
│   └── package.json
│
├── Dockerfile
├── docker-compose.yml
├── .gitignore
├── .env.example
└── README.md
```

---

# ⚙️ Installation Guide (Local Setup)

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Flight-Booking-App.git
cd Flight-Booking-App
```

---

## 2️⃣ Backend Setup

```bash
cd server
npm install
```

Create `.env` file inside `server/`

```
PORT=your port no
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_super_secret_key
```

Run backend:

```bash
node index.js
```

Server runs at:
```
http://localhost:6001
```

---

## 3️⃣ Frontend Setup

```bash
cd client
npm install
npm start
```

Frontend runs at:
```
http://localhost:3000
```

---




# 🧑‍💻 Features

## 👤 User
- Register
- Login
- Search Flights
- Book Flights
- View Bookings

## 🔑 Admin
- Admin Login
- Add Flights
- Update Flights
- Delete Flights
- Manage Users
- View All Bookings

---

# 🛡 Security

- bcrypt password hashing
- JWT token authentication
- Protected routes
- Role-based access
- Environment variable protection


# 👨‍💻 Author

Krishna Chaitanya Karicheti

---

# 📜 License

This project is created for learning and portfolio purposes.
