# 🚚 Last Mile Delivery Tracker (Customized Version)

A full-stack MERN-based logistics tracking system that manages order creation, delivery assignment, status tracking, and role-based access for Customers, Drivers, and Admins.

This project is based on an open-source MERN template and has been **modified, fixed, and improved for learning and deployment purposes**.

---

## 👨‍💻 Author Contributions

This project was originally based on an open-source template.

My contributions include:

- Fixed backend configuration and environment variable handling
- Secured `.env` file (removed from Git tracking and added to `.gitignore`)
- Fixed authentication issues (JWT login/register flow)
- Resolved MongoDB connection and credential issues
- Fixed email sending error (SMTP configuration issues)
- Improved error handling in backend APIs
- Cleaned and reorganized project structure
- Fixed GitHub deployment and push issues
- Successfully prepared project for Render deployment

---

## 🚀 Features

### 👤 User Roles
- Customer
- Driver
- Admin

### 🔐 Authentication
- JWT-based login/register system
- Role-based access control

### 📦 Delivery System
- Create delivery orders
- Assign drivers
- Track delivery status
- Update delivery progress

### 📧 Notifications
- Email notifications (fixed SMTP configuration issues)

---

## 🛠️ Tech Stack

- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB Atlas
- Authentication: JWT
- Deployment: Render

---

## ⚙️ Setup Instructions

### 1. Clone repository
```bash
git clone <your-repo-link>
cd last-mile-delivery-tracker
