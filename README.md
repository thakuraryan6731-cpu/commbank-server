# CommBank Backend

## 🚀 Overview
This is a backend API built using .NET and MongoDB for managing banking data such as Goals, Accounts, Transactions, and Users.

---

## 🛠️ Tech Stack
- .NET 6
- MongoDB Atlas
- ASP.NET Core Web API

---

## ⚙️ Setup Instructions

1. Clone the repository
git clone https://github.com/thakuraryan6731-cpu/commbank-server.git


3. Navigate to project folder
cd commbank-server


4. Add your MongoDB connection string in `appsettings.json`:
"MongoDbSettings": {
"ConnectionString": "<your_connection_string>",
"DatabaseName": "commbank"
}


5. Run the server

6. 
---

## 📌 API Endpoints

### Goals
- GET /api/Goal
- POST /api/Goal

### Accounts
- GET /api/Account
- POST /api/Account

---

## ⭐ Features
- MongoDB integration
- REST API with .NET
- CRUD operations
- Added optional `Icon` field to Goal model

---

## 🔐 Security
Sensitive data like database passwords are not stored in the repository.

---

## 👨‍💻 Author
Aryan Thakur
