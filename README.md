# 🕒 Attendance Management System

A full-stack **Attendance Management System** built for a client using **React** (frontend) and **Strapi** (backend).  
The application supports **role-based access control** with separate dashboards and features for **Admin, HR, Manager, and Employee**.

---

## 🚀 Key Features

### 🔐 Authentication & Authorization
- Login & Registration
- Role-based access control
- Dedicated dashboards for each role

---

## 📊 Dashboard Overview
- Real-time employee count
- Attendance summary:
  - Present
  - Late
  - Absent
- Pending actions:
  - Leave requests
  - Attendance justifications
  - Late entry requests

---

## 👥 Role-Based Features

### 🛠 Admin & HR
- Mark, edit, and delete attendance  
  *(One attendance entry per employee per day)*
- Manage employees:
  - Add
  - Edit
  - Delete
- Approve or reject:
  - Leave requests
  - Attendance justifications
- Generate payroll:
  - Late & absent deductions
  - Weekend exclusion
- Download employee salary slips

---

### 👔 Manager
- View-only access:
  - Attendance records
  - Employee list
  - Leave requests
  - Attendance justifications
- No create, edit, or approval permissions

---

### 👨‍💼 Employee
- View and edit own profile  
  *(Payment details only)*
- View own attendance with date filter
- Submit:
  - Leave requests
  - Attendance justifications
- View and download own payroll & salary slips

---

## 💰 Payroll System
- Automatic salary calculation based on attendance
- Deduction rules:
  - **3 late entries = 0.5 day deduction**
  - **1 absent = 1 full day deduction**
- Weekends are excluded from calculations
- Detailed CTC breakdown:
  - Basic
  - HRA
  - Transport Allowance
  - Other components

---

## 🎨 UI & UX Features
- Search functionality
- Notification system for:
  - Pending leave requests
  - Pending justifications
- Profile menu
- Dual logout buttons (header & profile)
- Clean and responsive UI

---

## 🛠 Tech Stack

### Frontend
- React
- JavaScript
- HTML
- CSS
- React Router

### Backend
- Strapi (Headless CMS)
- REST APIs
- Role & permission management

### Database
- Strapi-supported database (as configured)

---

## 📦 Installation & Setup

### Backend (Strapi)
```bash
cd backend
npm install
npm run develop
