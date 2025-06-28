# 🛒 E-Commerce Frontend (React + Material UI)

This is the frontend of a full-stack e-commerce application built with **React**, **Material UI**, and **Axios**. It supports user authentication, role-based admin features, a shopping cart, Stripe payment integration, and dynamic product listing.

## 🚀 Live Demo

👉 [Frontend on Vercel](https://your-frontend-url.vercel.app)  
👉 [Backend on Render](https://your-backend-url.onrender.com)

---

---

## ⚙️ Tech Stack

- **React**
- **Material UI (MUI)**
- **Axios**
- **React Router**
- **Stripe (Checkout)**
- **JWT Auth via Backend**
- **React-Bootstrap (for modals & toast)**

---

## 🔐 Features

### 👥 User
- Register & Login with JWT
- Browse products
- Add to cart
- Checkout with Stripe
- View order history

### 🛠️ Admin
- Add, Edit, Delete products
- Upload images
- Role-based access for product management

---

## 📁 Folder Structure
src/
├── api/
│ └── axios.js
├── components/
│ ├── Navbar.jsx
│ ├── ProductCard.jsx
│ ├── Cart.jsx
│ └── ...
├── pages/
│ ├── Home.jsx
│ ├── MyOrders.jsx
│ ├── AdminPanel.jsx
│ └── ...
├── utils/
├── App.js
└── index.js

## 🔧 Setup Instructions

```bash
git clone (https://github.com/Ru5hic10/ecommerce-frontend.git)
cd ecommerce-frontend
npm install

## .env
VITE_STRIPE_PUBLISHABLE_KEY=Your stripe key

##dependencies

npm install axios react-router-dom @mui/material @emotion/react @emotion/styled
