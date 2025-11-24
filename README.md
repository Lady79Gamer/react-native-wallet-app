# 💰 React Native Wallet App

A full-stack personal finance wallet application built using **React Native, Expo, Express, Clerk, Neon PostgreSQL, and Redis**.
This project demonstrates how to build a complete production-ready mobile application with **authentication, database integration, cloud deployment, and real-time updates** — all without needing Swift, Kotlin, or native modules.

This project demonstrates how to build a fully functional, production-ready mobile finance tracker using React Native + Expo alongside a Node.js/Express backend with:

⦁	Clerk authentication (with email code verification)

⦁	Neon PostgreSQL for database storage

⦁	Redis rate limiting

⦁	Deployed backend and real device mobile support

Users can:

⦁	Sign up & log in using a 6-digit email code

⦁	View their current wallet balance

⦁	Create income or expense transactions

⦁	Delete transactions, with recalculations

⦁	Pull-to-refresh to sync with backend

⦁	Log out securely

Perfect for developers looking to learn how to connect a mobile frontend to a real backend with secure user accounts and persistent cloud data storage.

---

## 🚀 Features

### ✨ Mobile App (Expo & React Native)

* 📱 Runs on **iOS & Android**
* 🔐 Email-based login & signup (6-digit verification code) using Clerk
* 💼 Home screen showing:

  * Current balance
  * List of transactions
* ➕ Add income and expense transactions
* 🔄 Pull-to-refresh functionality
* ❌ Delete transactions to update balance instantly
* 🚪 Logout routing that safely returns users to auth pages

### 🖥 Backend (Express API)

* 🌐 Fully REST-based Node.js server
* 🗄 PostgreSQL database hosted on Neon
* ⚙ Auth middleware using Clerk
* 📦 Redis-based rate limiting for protection
* ☁ Easily deployable on cloud services

---

## 🧠 What You'll Learn

By building this project, you’ll master:

* Building a **mobile app with React Native & Expo**
* Creating a **backend with Express & PostgreSQL**
* Real-world user authentication with **Clerk**
* Structured full-stack communication between mobile → backend → database
* Implementing rate limiting using **Redis**
* Deployment of both backend & mobile applications
* Managing navigation & global app state cleanly

Perfect for:

* Beginners building their *first full-stack mobile app*
* React developers expanding into React Native
* Anyone needing a realistic production-ready example

---


## 📸 App Screenshots

![Screenshot_2025-11-24-17-34-06-40_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/8c5bc732-129b-4d3f-bd56-d62f90f53d44)

![Screenshot_2025-11-24-17-35-00-45_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/683f9235-6ce8-4e59-b81f-a2a2c31f8647)

![Screenshot_2025-11-24-17-35-29-94_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/54cb127d-af9d-4090-8ebc-8bb97f4aba60)

![Screenshot_2025-11-24-17-35-38-40_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/952ec8bc-bd2d-4383-828f-8d77ea17f264)

![Screenshot_2025-11-24-17-35-54-52_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/9dfa3dcc-eed6-44ea-9940-e435c3e567ac)

![Screenshot_2025-11-24-17-37-17-80_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/71023d2b-e806-4479-895a-0e092cb5d19a)

![Screenshot_2025-11-24-17-37-26-39_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/33c657f0-4bb5-4a45-9904-c525f53d6799)

![Screenshot_2025-11-24-17-37-44-86_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/26565a89-cad3-4a85-8152-ccd427edef1b)

![Screenshot_2025-11-24-17-38-20-03_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/65e9a836-71e0-45d7-b55b-4cbd4e2e433c)

![Screenshot_2025-11-24-17-38-43-75_f73b71075b1de7323614b647fe394240](https://github.com/user-attachments/assets/192a4264-b862-4225-bf0c-b16ee74779c7)

---

## 🛠 Tech Stack

### Frontend

* React Native (Expo)
* React Navigation
* Async Storage
* Clerk Auth SDK

### Backend

* Node.js + Express
* PostgreSQL (Neon)
* Redis (Rate Limiting)
* Clerk Server SDK

---

## 📁 Project Structure

```
.
├── backend
│   ├── src
│   ├── package.json
│   └── .env
└── mobile
    ├── screens
    ├── components
    ├── package.json
    └── app.config.js
```

---

## ⚙ Environment Variables

### Backend (`/backend/.env`)

```
PORT=5001
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

DATABASE_URL=<your_neon_postgres_connection_url>
REDIS_URL=<your_redis_connection_url>
```

### Mobile (`/mobile/.env`)

```
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_key>
```

---

## ▶ Running The Project

### 1️⃣ Start Backend

```bash
cd backend
npm install
npm run dev
```

### 2️⃣ Start Mobile App

```bash
cd mobile
npm install
npx expo start
```

Scan the QR code or run the Android/iOS simulator.

---

## 📡 Deployment

You can deploy using:

### Backend:

* Vercel
* Render
* Fly.io
* Railway

### Database:

* Neon PostgreSQL (recommended)

### Redis:

* Upstash (free tiers available)

### Mobile:

* Expo EAS (supports OTA & store publishing)

---

## 📌 Roadmap

* [ ] Dark mode UI
* [ ] Filtering & sorting transactions
* [ ] Budget goals overview
* [ ] Push notifications for expenses

---

## 🧾 License

This project is open-source — see `LICENSE` for details.

---

## ⭐ Support

If this project helps you:

* Star ⭐ the repository
* Share with developers getting into React Native

## 🧾 Note
This backend is an API server. Opening the Render URL in a browser will not show a webpage — it is meant to serve the mobile app. If you open it directly, you may see “Cannot GET /”.

Thanks,
Happy coding!
aar0gya
