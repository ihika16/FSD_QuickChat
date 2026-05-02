# 💬 QuickChat – Full Stack Chat Application

QuickChat is a full-stack real-time chat application that allows users to communicate instantly with secure authentication and efficient backend services.

---

## 🚀 Features

* 🔐 User Authentication (JWT-based Login & Signup)
* 💬 Real-time Messaging System
* 👥 One-to-One Chat Functionality
* 📦 REST API Integration
* ⚡ Fast Backend with Express.js
* 📱 Responsive UI using React
* 🔒 Protected Routes & Middleware

---

## 🛠️ Tech Stack

### Frontend (client)

* React.js
* Vite
* CSS / Tailwind (if used)

### Backend (server)

* Node.js
* Express.js
* MongoDB (Mongoose)

---

## 📂 Project Structure

```
QuickChat/
│
├── client/                  # React frontend
│   ├── src/
│   └── package.json
│
├── server/                  # Backend (API + DB)
│   ├── models/              # User & Message schemas
│   ├── routes/              # API routes
│   ├── middleware/          # Auth middleware
│   ├── lib/                 # Utility functions
│   ├── server.js            # Entry point
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ihika16/FSD_QuickChat.git
cd FSD_QuickChat
```

---

### 2️⃣ Setup Backend

```bash
cd server
npm install
npm start
```

---

### 3️⃣ Setup Frontend

```bash
cd client
npm install
npm run dev
```

---

## 🌐 Environment Variables

Create a `.env` file inside `server/`:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 🔗 API Overview

### Auth Routes

* POST `/api/users/register`
* POST `/api/users/login`

### Message Routes

* GET `/api/messages`
* POST `/api/messages`

---

## 🚀 Deployment

* Frontend → Vercel
* Backend → Render / Railway

---

## 📸 Screenshots

(Add your UI screenshots here for better presentation)

---

## 🎯 Future Improvements

* Group chat feature
* File/image sharing
* Online/offline status
* Notifications

---

## 👨‍💻 Author

**Ihika**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
