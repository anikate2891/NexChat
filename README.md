# 💬 NexChat AI

> A ChatGPT-style AI chat application — unlimited access, no tier limits.


---

## 🚩 Problem

Free tiers of AI tools like Claude, ChatGPT, and others run out quickly — leaving users stuck mid-conversation with no access to AI assistance.

## ✅ Solution

**NexChat AI** is a full-stack AI chat application built with the MERN stack that gives users a smooth, ChatGPT-like experience — without worrying about running out of tokens or hitting a paywall. Just sign up, verify your email, and start chatting.

---

## 🌐 Live Demo

🔗 [https://nex-chat-frontend-phi.vercel.app/](https://nex-chat-frontend-phi.vercel.app/)

---

## ✨ Key Features

### 🔐 Authentication System
Secure user registration and login with JWT-based authentication to keep every user's data protected.

### 📧 Email Verification via Nodemailer
Users verify their email address during sign-up using Nodemailer — ensuring real accounts only.

### 🕓 Chat History
All your conversations are saved and accessible anytime — just like ChatGPT, pick up right where you left off.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Auth | JWT |
| Email | Nodemailer |
| Deployment | Vercel (Frontend) |

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)
- A Gmail account (for Nodemailer)

### Installation

```bash
# Clone the repo
git clone <your-github-link>
cd nexchat-ai

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file in the `/server` directory:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_gmail@gmail.com
EMAIL_PASS=your_gmail_app_password
```

### Run the App

```bash
# Start backend
cd server
npm run dev

# Start frontend
cd client
npm start
```

---

## 📁 Project Structure

```
nexchat-ai/
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
├── server/          # Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── index.js
└── README.md
```

---

## 🙋‍♂️ Author

Built with ❤️ as part of a personal project portfolio.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
