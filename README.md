# 🏥 Healthcare Appointment Booking using MERN

### 🚀 [🌐 Project Demo Link](https://drive.google.com/file/d/14QlsjXGk4wvU7D_0lv3FPq-MyTA-9Irk/view?usp=drive_link)

---

## 🩺 Overview

A full-stack web application built with the **MERN stack** that allows patients to book appointments with doctors.  
Admins and doctors can manage their schedules, appointments, and patient records.  
Users can register, log in, search for doctors, and book appointments online.

---

## 🚀 Tech Stack / Tools & Libraries Used

### 🔧 Frontend (React.js)
- **React.js** – UI development  
- **React Router** – Routing between pages  
- **Axios** – For HTTP requests  
- **Tailwind CSS** – Styling  
- **React Toastify** – Notifications & alerts  

### 🖥️ Backend (Node.js + Express.js)
- **Node.js** – Backend runtime  
- **Express.js** – REST API & routing  
- **Mongoose** – MongoDB object modeling  

### 🛢️ Database
- **MongoDB Atlas** – Cloud-hosted NoSQL database  

### 🔒 Authentication & Security
- **JWT (JSON Web Tokens)** – Secure user sessions  
- **bcryptjs** – Password hashing  

---

## ✨ Features

- ✅ User Registration & Login  
- ✅ Role-Based Access (Patient / Doctor / Admin)  
- ✅ Book & Cancel Appointments  
- ✅ View Available Time Slots  
- ✅ Doctor Profile Management  
- ✅ Admin Dashboard (Manage Doctors, Users, Appointments)  
- ✅ Responsive UI (Mobile + Desktop)  

---

## 🧗 Challenges Faced & Solutions

### 1️⃣ Role-Based Access Control
- **Challenge**: Differentiating views and permissions  
- **Solution**: Used JWT with role attributes and protected routes on both frontend and backend  

### 2️⃣ Appointment Conflicts
- **Challenge**: Preventing overlapping bookings  
- **Solution**: Implemented server-side validation for time slot availability  

### 3️⃣ Time Slot Management
- **Challenge**: Generating and updating available time slots dynamically  
- **Solution**: Created helper functions to manage doctor schedules and availability  

### 4️⃣ State Management
- **Challenge**: Sharing state like user info and appointments across components  
- **Solution**: Used **React Context API** and **localStorage** for session persistence  


---
## 📌 Improvements with More Time

- 🗓️ Calendar view for doctors  
- 📧 Email & SMS notifications  
- 💳 Payment gateway integration (e.g., Stripe)    
- 🌐 Multi-language support  
