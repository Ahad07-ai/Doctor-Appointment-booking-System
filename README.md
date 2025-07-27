# 🩺 Prescripto – Doctor Appointment Booking System

Prescripto is a full-stack web application that enables users to book appointments with doctors and provides admin-level access to manage bookings and user data. It features separate portals for users and administrators, with a responsive frontend and a robust backend API.

---

## 📂 Project Structure

prescripto-full-stack/
├── frontend/ → Main user interface (React + Tailwind + Vite)
├── admin/ → Admin dashboard (React + Tailwind + Vite)
├── backend/ → RESTful API server (Node.js + Express + MongoDB)

yaml
Copy
Edit

---

## 🚀 Features

### 🧑‍⚕️ User Frontend (`/frontend`)
- Book and manage doctor appointments
- View available doctors and time slots
- Responsive UI built with Tailwind CSS
- Hosted-ready using Vite + React

### 🛡 Admin Panel (`/admin`)
- Admin login and dashboard
- Manage doctors, users, and appointments
- Track overall system activity

### 🧠 Backend (`/backend`)

- RESTful APIs for appointments, doctors, users
- MongoDB models and controllers
- Centralized routing and middleware

---

## ⚙️ Tech Stack

| Layer    | Tech Used                         |
|----------|----------------------------------|
| Frontend | React, Vite, Tailwind CSS        |
| Backend  | Node.js, Express.js, MongoDB     |
| DevOps   | Vercel (frontend hosting), dotenv for secrets |

---

## 🛠 Installation & Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/Ahad07-ai/Doctor-Appointment-booking-System.git
cd Doctor-Appointment-booking-System
