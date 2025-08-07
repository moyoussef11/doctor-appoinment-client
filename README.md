# Doctor Appointment System – Client

A responsive frontend application for booking and managing doctor appointments.

This project allows admins to add doctors categorized by specialization. Users can register, book or cancel appointments, edit their profiles, and doctors can accept or reject appointments through their dedicated dashboard.

---

## 🚀 Tech Stack

- React.js
- Redux Toolkit
- Tailwind CSS
- Axios
- React Router DOM
- Ant Design (for dashboard UI)

---

## 🧰 Features

- User registration and login system
- Admin dashboard to:
  - Add doctors
  - Manage doctor listings
- Doctor dashboard to:
  - View, accept or reject appointments
- User features:
  - Book/cancel appointments
  - Edit profile information
- Authentication and protected routes
- Dynamic doctor listing by specialization
- Clean and responsive UI design

---

## 📂 Folder Structure (Main)

```bash
src/
├── components/        # Reusable components (Navbar, Footer, etc.)
├── pages/             # Main pages (Login, Register, Home, Profile, etc.)
├── rtk/             # Redux store, slices
├── utils/             # Helper functions 
└── App.jsx

🛠️ Installation
git clone https://github.com/moyoussef11/doctor-appoinment-client.git
cd doctor-appoinment-client
npm install
npm run dev

