# 💳 Mobile Banking System

A mobile banking application developed using **Flutter** with a **Node.js & Express.js REST API** and **TiDB Cloud (MySQL)** database. The project demonstrates full-stack mobile application development by integrating a Flutter frontend with a cloud-hosted backend to perform basic banking operations.

## ✨ Features

- Deposit money
- Withdraw money
- View account balance
- Display deposit history
- Display withdrawal history
- Contact Us page
- REST API integration
- Cloud database connectivity

---

## 🛠️ Tech Stack

### Frontend
- Flutter
- Dart

### Backend
- Node.js
- Express.js

### Database
- TiDB Cloud (MySQL)

### API
- RESTful API
- HTTP
- JSON

---

## 📁 Project Structure

```
lib/
├── screen/
│   ├── contact_us_screen.dart
│   ├── deposit_screen.dart
│   └── withdraw_screen.dart
│
└── main.dart

Backend/
├── index.js
├── package.json
├── package-lock.json
└── .env
```

> **Note:** `index.js` contains the Express.js REST API used by the Flutter application for backend communication.

---

## 📡 REST API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/` | API Status |
| GET | `/deposit` | Retrieve all deposit records |
| POST | `/deposit` | Create a new deposit transaction |
| GET | `/withdraw` | Retrieve all withdrawal records |
| POST | `/withdraw` | Create a new withdrawal transaction |
| GET | `/balance` | Retrieve current account balance |

---

## ⚙️ Backend Features

- RESTful API using Express.js
- Cloud-hosted MySQL database on TiDB Cloud
- Automatic balance update after deposits
- Automatic balance deduction after withdrawals
- JSON request and response handling
- CORS support
- Environment variable configuration using dotenv

---

## 🎯 Learning Outcomes

This project was developed to gain practical experience in:

- Flutter mobile application development
- REST API development
- Backend development with Node.js & Express.js
- Database integration using TiDB Cloud
- Client-server architecture
- CRUD operations
- Full-stack application development

---

## 👨‍💻 Team Members

| Name | Student ID |
|------|------------|
| Kaung Khant Lwin | 6703114 |
| **Min Sitt Paing Oo** | 6704524 |
| Thura Hein | 6704639 |

---

**Academic Project** • Developed as part of a university coursework assignment.
