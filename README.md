# 🏦 Banking System

A backend banking system built with **Node.js, Express.js, MongoDB, and Mongoose**, designed to simulate core banking operations and practice real-world backend development.

## 🚀 Features

* User registration, login & logout
* JWT-based authentication
* Password hashing with bcrypt
* Bank account creation
* Account balance management
* Money transfers between accounts
* MongoDB transaction sessions
* Debit & credit ledger system
* Transaction status handling
* Idempotency support
* System account for initial funds
* Email service with Nodemailer
* Authentication middleware
* Organized MVC-style structure

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* bcrypt
* Nodemailer
* Cookie Parser
* dotenv

## 📁 Project Structure

```text
Banking System/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── app.js
├── server.js
├── package.json
├── package-lock.json
└── .env
```

## ⚙️ Installation

```bash
git clone <your-repository-url>
cd "Banking System"
npm install
```

Create a `.env` file and add your required environment variables.

## ▶️ Run the Project

```bash
node server.js
```

For development with Nodemon:

```bash
npx nodemon server.js
```

## 🔐 Security

Sensitive credentials and environment variables should **never be committed to GitHub**. Add `.env` to `.gitignore`.

## 📌 Purpose

This project was built to strengthen backend development skills and understand concepts such as **authentication, database relationships, financial transactions, data consistency, and ledger-based transaction tracking**.
