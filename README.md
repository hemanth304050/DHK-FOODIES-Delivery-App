## DHK-FOODIES-Delivery-App

# Project Title:- 

## OrderOnTheGo: Your On-Demand Food Ordering Solution(DHK-FOODIES-Delivery-App)

Full Stack Development with MERN.

DHK FOODIES is a comprehensive online food ordering and delivery platform designed to streamline the process of connecting customers with their favorite restaurants. It provides a seamless user experience with real-time menu Browse, cart management, and order placement.

## 📂 Project Features

✅ User Authentication: Secure login and registration for customers.

✅ Browse Restaurants and Menus: View a dynamic list of available restaurants and their detailed menus.

✅ Add to Cart Functionality: Easily add and manage food items in a shopping cart.

✅ Real-time Order Placement: A smooth and simple checkout process to place food orders.

✅ Admin Panel: A potential feature for managing restaurants, users, and orders.

✅ Responsive UI: A clean and intuitive user interface built with React.

## 🛠️ Tech Stack

Frontend: React.js

Backend: Node.js, Express.js

Database: MongoDB

📁 Project Folder Structure


## ├── client      # React Frontend
## ├── server      # Express Backend API
## └── seeder.js   # Script to import initial data
## 🚀 Setup Instructions

Prerequisites
Node.js

NPM

MongoDB

Installation
Bash

## Install backend dependencies
cd server
npm install

## Install frontend dependencies
cd ../client
npm install
Database Seeding
This project requires initial data (restaurants, menus) to function correctly. A seeder script has been provided to populate the database.

Bash

## From the root directory, navigate to the server
cd server

## Run the seeder script to import data
node seeder.js.
## 🖥️ Running the Application
First, ensure your local MongoDB server is running. Then, open two separate terminals:

Bash

## In Terminal 1: Start the Backend
cd server
npm start

## In Terminal 2: Start the Frontend
cd client
npm start
The application will be available at the following locations:

Frontend: http://localhost:3000

Backend API: http://localhost:5000

## Deployed: https://dhkapk.netlify.app/

## 🔒 Authentication

Email & Password based authentication for users.

Planned future enhancement: JWT Security for API endpoints.

## 📋 API Endpoints
| Method | Endpoint                    | Description                       |
| :---   | :---                        | :---                              |
| POST   | /api/users/register         | Register a new user               |
| POST   | /api/users/login            | Login for users                   |
| GET    | /api/products               | Fetch list of all food/restaurants|
| POST   | /api/orders                 | Place a new food order            |

## 🖥️ User Interfaces

Login & Registration Pages

Home Page with Restaurant Listings

Restaurant Menu / Product Details Page

Shopping Cart & Checkout Page

User Profile / Order History Page

## 🧪 Testing

Backend APIs can be tested using tools like Postman.

Frontend components and user flows tested across modern browsers using Chrome DevTools.

## 👨‍💻 Team Members

1.Team Leader: Dhannodi Hemanth Kumar

2.Team member: Dandu Keerthi

3.Team member: Shaik Topivali

4.Team member: Yakasi Keerthi

6.Team member: Leela Siddu
## 🎥 Demo

A video demonstration of the project can be placed in a Video Demo folder within the project repository.

## 📌 Note
This project is developed for academic and learning purposes, focusing on the core principles of MERN stack development and application structure.
## Link --> https://dhkapk.netlify.app/
