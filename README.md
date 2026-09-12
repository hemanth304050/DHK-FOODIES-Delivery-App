# 🍔 DHK-FOODIES-Delivery-App

> 🛵 **OrderOnTheGo: Your On-Demand Food Ordering Solution** — a full-stack MERN food ordering and delivery platform that connects customers with their favorite restaurants.

---

## 📌 Project Overview

**DHK FOODIES** is a comprehensive online food ordering and delivery platform designed to streamline the process of connecting customers with their favorite restaurants.

It provides a seamless user experience with:

- 🍽️ Real-time menu browsing
- 🛒 Cart management
- 📦 Order placement

Built as a **Full Stack MERN** project for academic and learning purposes.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🔐 User Authentication | Secure login and registration for customers |
| 🏬 Browse Restaurants & Menus | View a dynamic list of restaurants and detailed menus |
| 🛒 Add to Cart | Easily add and manage food items in a shopping cart |
| ⚡ Real-time Order Placement | Smooth and simple checkout process |
| 🛠️ Admin Panel | Potential feature for managing restaurants, users, and orders |
| 📱 Responsive UI | Clean and intuitive interface built with React |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| 🎨 Frontend | React.js |
| ⚙️ Backend | Node.js, Express.js |
| 🗄️ Database | MongoDB |

---

## 📂 Project Structure

```

📦 DHK-FOODIES-Delivery-App
 ┣ 📁 client         # React Frontend
 ┣ 📁 server         # Express Backend API
 ┣ 📄 seeder.js      # Script to import initial data
 ┣ 📁 Documentation
 ┣ 📁 Project Report
 ┣ 📁 Video Demo
 ┗ 📜 README.md
```

---

## 🚀 Setup Instructions

### ✅ Prerequisites

- 🟢 Node.js
- 📦 NPM
- 🍃 MongoDB

### ⚙️ Installation

**Install backend dependencies**

```bash
cd server
npm install
```

**Install frontend dependencies**

```bash
cd ../client
npm install
```

---

## 🌱 Database Seeding

This project requires initial data (restaurants, menus) to function correctly. A seeder script is provided to populate the database.

```bash
# From the root directory, navigate to the server
cd server

# Run the seeder script to import data
node seeder.js
```

---

## 🖥️ Running the Application

First, ensure your local MongoDB server is running. Then open **two separate terminals**:

**Terminal 1 — Start the Backend**

```bash
cd server
npm start
```

**Terminal 2 — Start the Frontend**

```bash
cd client
npm start
```

The application will be available at:

- 🎨 Frontend: `http://localhost:3000`
- ⚙️ Backend API: `http://localhost:5000`

🌐 **Deployed:** [dhkapk.netlify.app](https://dhkapk.netlify.app/)

---

## 🔒 Authentication

- 📧 Email & password-based authentication for users
- 🔮 Planned future enhancement: JWT security for API endpoints

---

## 📋 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/users/register` | Register a new user |
| POST | `/api/users/login` | Login for users |
| GET | `/api/products` | Fetch list of all food/restaurants |
| POST | `/api/orders` | Place a new food order |

---

## 🖥️ User Interfaces

- 🔑 Login & Registration Pages
- 🏠 Home Page with Restaurant Listings
- 🍽️ Restaurant Menu / Product Details Page
- 🛒 Shopping Cart & Checkout Page
- 👤 User Profile / Order History Page

---

## 🧪 Testing

- 🧰 Backend APIs tested using tools like Postman
- 🌐 Frontend components and user flows tested across modern browsers using Chrome DevTools

---

## 👨‍💻 Team Members

| # | Role | Name |
|---|------|------|
| 1️⃣ | 👑 Team Leader | Dhannodi Hemanth Kumar |
| 2️⃣ | 🤝 Team Member | Dandu Keerthi |
| 3️⃣ | 🤝 Team Member | Shaik Topivali |
| 4️⃣ | 🤝 Team Member | Yakasi Keerthi |
| 5️⃣ | 🤝 Team Member | Leela Siddu |

---

## 🎥 Demo

A video demonstration of the project is available in the **Video Demo** folder within the repository.

---

## 📌 Note

> 🚨 This project is developed for **academic and learning purposes**, focusing on the core principles of MERN stack development and application structure.

---

## 🔗 Live Link

🌐 **[https://dhkapk.netlify.app/](https://dhkapk.netlify.app/)**

---

## ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork the repository
- 🐛 Report issues
- 💡 Suggest improvements

---

## 📜 License

This project is intended for educational and learning purposes.

---

<div align="center">

🍔 **DHK-FOODIES-Delivery-App**

Built with ❤️ using the MERN Stack

⭐ Star the repository if you like it!

</div>
