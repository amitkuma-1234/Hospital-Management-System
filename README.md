markdown# 🏥 Hospital Management System

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-Framework-black?style=for-the-badge&logo=express)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)
![HTML](https://img.shields.io/badge/HTML-Frontend-orange?style=for-the-badge&logo=html5)
![CSS](https://img.shields.io/badge/CSS-Styling-blue?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Logic-yellow?style=for-the-badge&logo=javascript)

**A full-stack hospital management system with role-based authentication for admin, doctors, and patients.**

[Features](#-features) • [Tech Stack](#-tech-stack) • [Roles](#-user-roles) • [Installation](#-installation)

</div>

---

## 🚀 What is Hospital Management System?

Hospital Management System is a **full-stack web application** built with Node.js, Express.js, and MySQL that streamlines hospital operations. It provides role-based access for **Admin, Doctors, and Patients** with features like appointment scheduling, patient record management, secure session handling, and admin workflow automation.

> 💡 *Login as Admin / Doctor / Patient → Access role-specific dashboard → Manage hospital operations efficiently*

---

## ✨ Features

- 🔐 **Role-Based Authentication** – Separate login & dashboard for Admin, Doctor, and Patient
- 📅 **Appointment Scheduling** – Patients can book, view, and manage appointments
- 🗂️ **Patient Record Management** – Store and retrieve complete patient medical history
- 👨‍⚕️ **Doctor Management** – Admin can add, update, and manage doctor profiles
- 🔒 **Secure Session Handling** – Server-side session management for data security
- 🛢️ **MySQL Database Schema** – Well-structured relational database design
- ⚙️ **Admin Workflow Automation** – Automate hospital administrative tasks
- 🌐 **Responsive Frontend** – Clean and intuitive UI with HTML, CSS & JavaScript

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML & CSS** | Frontend UI & styling |
| **JavaScript** | Client-side interactivity |
| **Node.js** | Backend runtime environment |
| **Express.js** | Web framework & REST API |
| **MySQL** | Relational database |
| **Express Session** | Secure session management |

---

## 👥 User Roles

### 🔑 Admin
- Manage doctors & patients
- View all appointments
- Automate hospital workflows
- Full system control

### 👨‍⚕️ Doctor
- View assigned patient records
- Manage appointments
- Update patient medical history

### 🧑‍💼 Patient
- Register & login securely
- Book & track appointments
- View personal medical records

---

## ⚙️ How It Works
User logs in (Admin / Doctor / Patient)
↓
Role verified via session authentication
↓
Role-specific dashboard loaded
↓
User performs actions (book appointment, view records, manage doctors)
↓
Data stored / retrieved from MySQL database via Express.js API
↓
Response rendered on frontend

---

## 📁 Project Structure
Hospital-Management-System/
│
├── hospital_managment_system.zip    # Main project files
└── README.md

---

## 🔧 Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/amitkuma-1234/Hospital-Management-System.git
   cd Hospital-Management-System
```

2. **Extract the zip:**
```bash
   unzip hospital_managment_system.zip
```

3. **Install dependencies:**
```bash
   npm install
```

4. **Setup MySQL database:**
```sql
   CREATE DATABASE hospital_db;
   -- Import the provided SQL schema file
```

5. **Configure environment variables:**
```env
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=yourpassword
   DB_NAME=hospital_db
   SESSION_SECRET=your_secret_key
```

6. **Run the server:**
```bash
   node app.js
```

7. **Open in browser:**
http://localhost:3000

---

## 📌 Use Cases

- 🏥 Small & mid-size hospital management
- 🩺 Clinic appointment & record tracking
- 🎓 Academic full-stack web development project
- 💼 Healthcare admin automation demo

---

## 🙋‍♂️ Author

<div align="center">

**Amit Kumar**

[![GitHub](https://img.shields.io/badge/GitHub-amitkuma--1234-black?style=for-the-badge&logo=github)](https://github.com/amitkuma-1234)

⭐ **If you find this useful, please give it a star!** ⭐

</div>

---

<div align="center">
Made with ❤️ using Node.js + Express.js + MySQL
</div>
