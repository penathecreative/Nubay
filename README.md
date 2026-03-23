# 🛍️ Full Stack E-Commerce Application

A full-stack e-commerce application designed to simulate a real-world online store, including authentication, product management, order processing, and online payments.

This project demonstrates my ability to build and connect a complete system from frontend to backend, handling real-world challenges such as state management, protected routes, and payment integration.

---

## 🚀 Live Demo

* 🌐 Frontend: *(add your Vercel link here)*
* 🔧 Backend API: *(add your backend link if deployed)*

---

## 🧠 Project Overview

This application allows users to:

* Browse products
* Add items to cart
* Complete purchases using PayPal
* View order details

It also includes an **admin panel** where administrators can:

* Manage products (create, update, delete)
* View and manage customer orders
* Update order statuses

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* Redux Toolkit
* React Router
* Axios
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication

### Payments

* PayPal Integration

---

## 🔐 Key Features

* 🔑 Secure authentication using JWT
* 🛒 Persistent cart management
* 💳 PayPal payment integration
* 📦 Order creation and tracking
* 🧑‍💼 Admin dashboard with protected routes
* 🔄 Async state management with Redux Toolkit
* 🌐 RESTful API architecture
* ⚠️ Real-world debugging (API errors, Redux serialization issues, auth issues)

---

## 📁 Project Structure

```id="6bpv9c"
ecommerce-project/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── controllers/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── redux/
│   └── components/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```id="nq4yxf"
git clone <your-repo-url>
cd ecommerce-project
```

---

### 2. Setup Backend

```id="x6czcd"
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```id="uk2dlb"
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
```

Run backend:

```id="n6r3qr"
npm run dev
```

---

### 3. Setup Frontend

```id="2t5x2s"
cd frontend
npm install
npm run dev
```

---

## 🧪 What This Project Demonstrates

* Building a full-stack application from scratch
* Designing RESTful APIs
* Managing global state with Redux Toolkit
* Implementing authentication and protected routes
* Integrating third-party services (PayPal)
* Handling asynchronous operations and API communication
* Debugging real-world production-like issues

---

## 📈 Future Improvements

* ☁️ Cloud architecture (AWS, Docker, CI/CD pipelines)
* 📦 Image hosting (Cloudinary or similar)
* 🧪 Unit & integration testing
* ⚡ Performance optimization
* 📊 Admin analytics dashboard

---

## 📌 Notes

This project is part of my journey as a **Junior Full Stack Developer**, focusing on building real-world applications and improving system design, scalability, and maintainability.

---

## 👨‍💻 Author

Bruno Fernandes
Full Stack Developer
Based in the Netherlands

---

## ⭐ Final Thoughts

This project reflects hands-on experience with real-world development challenges, including authentication, state management, backend integration, and payment systems.

Feedback is always welcome.
