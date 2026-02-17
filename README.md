# 💬 MERN Chat App

A modern full-stack real-time chat application built using the MERN Stack.  
This app allows users to connect instantly, create conversations, and chat in real-time with secure authentication.

---

## 🚀 Features

- 🔐 User Authentication (Login / Signup)
- 💬 One-to-One Real-Time Chat
- 👥 Create & Manage Group Chats
- 🔔 Real-Time Notifications
- ✍️ Typing Indicators
- 🔍 Search Users
- 👤 View User Profiles
- ➕ Add / Remove Users from Groups
- 🔒 Secure Password Encryption
- ⚡ Socket.io for Live Communication

---

## 🛠️ Tech Stack

### Frontend
- React JS
- Axios
- Context API

### Backend
- Node JS
- Express JS
- Socket.io

### Database
- MongoDB (Mongoose)

---

## 📂 Project Structure

```
MERN-CHAT-APP
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   └── server.js
│
├── frontend
│   ├── src
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup (Run Locally)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/kashishbhutia/MERN-CHAT-APP.git
```

### 2️⃣ Go into the project folder

```bash
cd MERN-CHAT-APP
```

### 3️⃣ Install backend dependencies

```bash
npm install
```

### 4️⃣ Install frontend dependencies

```bash
cd frontend
npm install
```

---

## 🔑 Environment Variables Setup

Create a `.env` file inside the **backend folder** and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

⚠️ Make sure `.env` is added in `.gitignore`.

---

## ▶️ Run the Application

### Start Backend

```bash
npm start
```

### Start Frontend (Open new terminal)

```bash
cd frontend
npm start
```

The app will run on:

```
http://localhost:3000
```

---

## 🌟 Key Highlights

- Real-time communication using WebSockets
- Clean UI & responsive design
- Secure authentication system
- Scalable backend structure
- Production-ready architecture

---

## 📌 Future Improvements

- Online/Offline Status
- Message Seen Indicators
- File Sharing
- Dark Mode
- Deployment on Cloud

---

## 👨‍💻 Developed By

**Kashish Bhutia**

---

⭐ If you like this project, feel free to star the repository!
