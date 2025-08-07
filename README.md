# 💰 Expenses Manager

A full-stack expense tracking application with a Spring Boot backend and React frontend.

---

## 📦 Tech Stack

### 🔙 Backend
- Java 17
- Spring Boot
- Spring Security + JWT
- Spring Data JPA (PostgreSQL)
- Spring Scheduler (Daily Reports)
- Gradle

### 🔜 Frontend
- React (Vite / CRA)
- Axios
- React Router
- Bootstrap or Tailwind

---

## 🌍 Live Demo

| Component     | URL |
|--------------|-----|
| 🎨 Frontend (GitHub Pages) | https://cinekenic.github.io/expense-manager-app |
| 🚀 Backend (Render)       | (https://expense-manager-restapi.onrender.com) |
| ☁️ DB or alt backend (Clever Cloud)

---

## 🔐 Authentication

App uses **JWT-based auth**. Secure endpoints require the token in `Authorization` header.

Example:

Authorization: Bearer eyJhbGciOiJIUzI1NiIsIn...

---

## 🧪 Features

- ✅ User Registration & Login
- 💼 Add / Update / Delete Expenses
- 📅 Daily summaries via Spring Scheduler
- 🔐 Role-based access control
- 📈 Reports API
- 💡 Clean REST API

---

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Node.js 18+
- mySQL DB

---

## ⚙️ Backend Setup
cd restapi
./gradlew bootRun

---

## 🎨 Frontend Setup
cd frontIO
npm install
npm run dev
App will run on http://localhost:3000
