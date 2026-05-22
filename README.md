# AI Habit Tracker

An AI-powered full-stack MERN application that helps users build consistency, track habits, analyze productivity trends, and receive personalized AI-generated insights.

## Live Demo

Frontend:
https://aihabittracker-kapil-garg.netlify.app

---

# 🏗️ System Architecture

<img width="1600" alt="Architecture Diagram" src="./screenshots/architecture.png" />

---

# 📸 Application Screenshots

---

## 🏠 Landing Page

<img width="1200" alt="Landing Page" src="./screenshots/landing.png" />

---

## 🔑 Login Page

<img width="1200" alt="Login Page" src="./screenshots/login.png" />

---

## 📋 Dashboard

<img width="1200" alt="Dashboard" src="./screenshots/dashboard.png" />

---

## 🎯 Habit Management

<img width="1200" alt="Habit Management" src="./screenshots/habits.png" />

---

## 📈 Statistics & Analytics

<img width="1200" alt="Statistics Dashboard" src="./screenshots/stats.png" />

---

## 🤖 AI Insights

<img width="1200" alt="AI Insights" src="./screenshots/insights.png" />)

---

## Features

- User Authentication
- Habit Creation & Tracking
- Daily Progress Monitoring
- AI-Based Suggestions
- Secure JWT Authentication
- Responsive UI

---

## Tech Stack

### Frontend
- React
- Vite
- Axios
- CSS

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- JWT Authentication

### Deployment
- Netlify (Frontend)
- Render (Backend)

---

## Project Structure

```bash
aihabittracker/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── .env
│   ├── package.json
│   └── server.js
│
├── frontend/
│   ├── public/
│   │   └── _redirects
│   │
│   ├── src/
│   │   ├── api/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   │
│   ├── .env
│   ├── package.json
│   └── vite.config.js
│
├── screenshots/
│   ├── architecture.png
│   ├── documentation.png
│   ├── landing.png
│   ├── login.png
│   ├── dashboard.png
│   ├── habits.png
│   ├── stats.png
│   └── insights.png
│
├── README.md
└── .gitignore
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/kapilgarg9358/aihabittracker.git
```

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

## Environment Variables

Backend `.env`

```env
MONGO_URI=
JWT_SECRET=
CLIENT_URL=
```

---

## Author

Kapil Garg