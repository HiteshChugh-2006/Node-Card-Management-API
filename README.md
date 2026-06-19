<div align="center">

# 🃏 Node Card Management API

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com/)

> **A RESTful Node.js + Express API for card management — featuring authentication, CRUD operations, and MongoDB integration.**

</div>

---

## ✨ Features

- 🔐 **JWT Authentication** — Secure token-based auth
- 📦 **Card CRUD** — Create, read, update, delete cards
- 🗄️ **MongoDB Models** — Mongoose schema validation
- 🔒 **Protected Routes** — Middleware-based route guards
- 📝 **Organised Routing** — Modular route handlers

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| Node.js | Runtime environment |
| Express.js | Web framework |
| MongoDB + Mongoose | Database & ODM |
| JWT | Authentication tokens |
| bcrypt | Password hashing |

## 🚀 Getting Started

```bash
git clone https://github.com/HiteshChugh-2006/Node-Card-Management-API.git
cd Node-Card-Management-API
npm install

# Configure environment
cp .env.example .env
# Add MONGO_URI and JWT_SECRET

npm start
```

## 📡 API Endpoints

| Method | Endpoint | Auth | Description |
|--------|----------|------|-------------|
| `POST` | `/api/auth/register` | ❌ | Register user |
| `POST` | `/api/auth/login` | ❌ | Login & get token |
| `GET` | `/api/cards` | ✅ | Get all cards |
| `POST` | `/api/cards` | ✅ | Create card |
| `PUT` | `/api/cards/:id` | ✅ | Update card |
| `DELETE` | `/api/cards/:id` | ✅ | Delete card |

## 📁 Project Structure

```
├── config/         # DB and environment config
├── models/         # Mongoose schemas
├── routes/         # Express route handlers
└── index.js        # Entry point
```

---

<div align="center">
Made with ❤️ by <a href="https://github.com/HiteshChugh-2006">Hitesh Chugh</a>
</div>