# Payroll Management System

A comprehensive Full-Stack Management System designed to automate employee salary processing, attendance tracking, and organizational management. This project serves as the final year project for the **Computer Engineering** program at **Pokhara University (NAST College)**.

---

## 👥 Project Team
* **Anil** (Technical Lead & Full-Stack Developer)
* **Bharat** (Technical Team)
* **Kabita** (Technical Team)
* **Salina** (Technical Team)

---

## 🚀 Tech Stack

### Frontend
* **React.js** (Vite)
* **CSS3** (Custom Layouts)
* **Axios** (API Integration)

### Backend
* **Java (Spring Boot)**
* **Spring Security** (Authentication & Authorization)
* **MySQL** (Database Management)

---

## 📂 Project Structure
This repository is a **Monorepo** containing both the client and server code:

```text
Payroll-Management-System/
├── frontend/           # React Application (Vite)
│   ├── src/
│   ├── public/
│   └── package.json
└── backend/            # Spring Boot Application (Java)
    ├── src/
    ├── pom.xml
    └── .mvn/
🛠️ Setup & Installation
Prerequisites
Node.js (v18+)

JDK (17 or 21)

MySQL Server

1. Database Setup
Create a MySQL database named payroll_db.

Update the backend/src/main/resources/application.properties with your MySQL username and password.

2. Run Backend (Spring Boot)
Bash
cd backend
mvn spring-boot:run
The server will start on http://localhost:8080

3. Run Frontend (React)
Bash
cd frontend
npm install
npm run dev
The app will be available at http://localhost:5173

✨ Key Features
User Roles: Admin, Accountant, and Employee dashboards.

Payroll Processing: Automated salary calculation, tax slab management, and deductions.

Attendance & Leave: Real-time attendance records and leave request workflows.

Reports: Generation of salary analytics and employee reports.

