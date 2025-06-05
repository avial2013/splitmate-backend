# SplitMate – Smart Shared Living App

## 📌 Overview

**SplitMate** is a full-stack web and mobile app built to simplify life for roommates. It helps manage shared expenses, chores, and household communication—streamlined in one smart platform.

Whether it's who takes out the trash or who owes who for groceries, SplitMate keeps things clear, fair, and automatic.

## 🚀 Live Demo

* 🌐 Web: \[link here]
* 📱 Mobile: \[Expo link here]
* 🔧 API Docs: \[Swagger link here]
* 📂 GitHub: \[[backend repo](https://github.com/avial2013/splitmate-backend.git)] | \[[frontend repo](https://github.com/avial2013/splitmate-frontend.git)]

## 🌟 Features

* 🔑 User Authentication (JWT + Refresh Tokens)
* 🏠 Household Management (create, join, invite)
* 📋 Chore Tracker (drag & drop Kanban-style)
* 💸 Expense Splitter (track who paid, who owes)
* 🧠 Smart Reminders (push + email)
* 📡 Real-Time Updates (WebSockets)
* 📊 Dashboard Overview (charts, lists, activity log)
* 🌍 Multilingual Support (Hebrew, English)

## 🛠️ Tech Stack

### Backend

* Node.js, Express.js, TypeScript
* MongoDB + Mongoose
* JWT Auth, Bcrypt
* WebSockets (Socket.IO)
* AWS / Railway (deployment)
* Swagger for API documentation

### Frontend (Web)

* React + TypeScript
* Zustand (state management)
* Styled Components or TailwindCSS
* React Hook Form + Zod

### Mobile

* React Native + Expo
* Shared logic with Web (hooks/services)
* Push Notifications (Expo)

### DevOps

* GitHub Actions (CI)
* Vercel (Web), Expo (Mobile)
* Logging with Winston
* MongoDB Atlas

## 🔮 Test Credentials (for demo)

Email: `demo@splitmate.com`
Password: `Split1234`

## 🗂️ Project Structure

```bash
.
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── utils
├── frontend
│   ├── components
│   ├── pages
│   ├── hooks
│   ├── services
│   └── state
└── mobile
    └── similar structure to frontend
```

## 👨‍💻 Developer

**Avial Israel**
Full Stack Developer • Node.js • React • AWS
🇮🇱 Israel
📧 [avicop@gmail.com](mailto:avicop@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/avial-israel/) | [Portfolio](https://yourportfolio.com)

---

## 📆 Architecture (To Be Added)

*(Insert architecture diagram using Excalidraw or Lucidchart here)*
