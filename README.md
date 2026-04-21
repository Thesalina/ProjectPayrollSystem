# Payroll Management System

> A comprehensive full-stack system to automate employee salary processing, attendance tracking, and organizational management.

**Final Year Project — Computer Engineering, Pokhara University (NAST College)**

![Java](https://img.shields.io/badge/Java-17%2F21-orange?style=flat-square&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat-square&logo=springboot)
![React](https://img.shields.io/badge/React-Vite-61DAFB?style=flat-square&logo=react)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=flat-square&logo=mysql)

---

## Overview

The Payroll Management System streamlines the core HR and finance operations of an organization. It handles multi-role access (Admin, Accountant, Employee), automates salary computation with configurable tax slabs and deductions, manages leave workflows, and generates detailed payroll reports — all within a secure, authenticated environment.

---

## 👥 Project Team

| Name | Role |
|------|------|
| **Anil** | Technical Lead & Full-Stack Developer |
| **Bharat** | Technical Team |
| **Kabita** | Technical Team |
| **Salina** | Technical Team |

---

## 🚀 Tech Stack

### Frontend
- **React.js** (Vite) — component-based UI framework
- **CSS3** — custom responsive layouts
- **Axios** — HTTP client for API integration

### Backend
- **Java** with **Spring Boot** — REST API server
- **Spring Security** — authentication & role-based authorization
- **MySQL** — relational database management

---

## ✨ Key Features

- **User Roles** — Separate dashboards and permissions for Admin, Accountant, and Employee.
- **Payroll Processing** — Automated salary calculation with configurable tax slabs and deductions.
- **Attendance & Leave** — Real-time attendance records and a structured leave request and approval workflow.
- **Reports & Analytics** — Exportable salary analytics and employee-level payroll reports.

---

## 📂 Project Structure

This is a monorepo containing both client and server code:

```
Payroll-Management-System/
├── frontend/           # React Application (Vite)
│   ├── src/
│   ├── public/
│   └── package.json
└── backend/            # Spring Boot Application (Java)
    ├── src/
    ├── pom.xml
    └── .mvn/
```

---

## 🛠️ Setup & Installation

### Prerequisites

| Tool | Version |
|------|---------|
| Node.js | v18 or higher |
| JDK | 17 or 21 |
| MySQL Server | 8.x recommended |

### 1. Database Setup

Create a MySQL database:

```sql
CREATE DATABASE payroll_db;
```

Then update your credentials in:

```
backend/src/main/resources/application.properties
```

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/payroll_db
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
```

### 2. Run the Backend (Spring Boot)

```bash
cd backend
mvn spring-boot:run
```

The server starts at **http://localhost:8080**

### 3. Run the Frontend (React + Vite)

```bash
cd frontend
npm install
npm run dev
```

The app is available at **http://localhost:5173**

---

## 🔐 Authentication

Authentication is handled by Spring Security. On first run, ensure the database schema is initialized (Spring Boot will auto-create tables if `spring.jpa.hibernate.ddl-auto=update` is set). Default admin credentials can be configured in the seed data or `application.properties`.





## 📄 License

This project was developed as a final year academic project at **NAST College, Pokhara University**. All rights reserved by the project team.



*Built with ♥ by Anil, Bharat, Kabita & Salina — Computer Engineering, Batch 2025*
