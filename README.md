# DHK-FOODIES-Delivery-App

DHK FOODIES - A Modern Food Ordering Web App
Full Stack Development with MERN (Frontend and backend)

DHK FOODIES is a feature-rich frontend & backend prototype for an online food ordering system. It is designed to demonstrate a seamless and intuitive user experience for discovering restaurants, filtering choices, placing orders, and managing a user profile. It offers real-time interactivity and a fully responsive design, all from a single HTML file.

📂 Project Features
✅ User Authentication: Login and Signup with password visibility toggle and persistent sessions using mongodb & localStorage

✅ User Profile Management: Automatically generated User ID and creation timestamp viewable on a dedicated Profile page. ✅ Advanced Restaurant Filtering: Filter restaurants by dietary preference (Veg/Non-Veg) and multiple food categories. ✅ Dynamic Sorting: Sort restaurant listings by price from "Low to High" or "High to Low." ✅ Interactive Menu Browsing: View detailed restaurant menus with items organized by category. ✅ Stateful Shopping Cart: Add, remove, and update item quantities with real-time total calculation. ✅ Complete Mock Checkout Flow: A multi-step process including a delivery address form and a detailed payment modal (Card, UPI, COD). ✅ Persistent Order History: View past orders with simulated status updates, saved to the user's profile. ✅ Fully Responsive UI: Built with Tailwind CSS to ensure a seamless experience on both desktop and mobile devices.

🛠️ Tech Stack
Frontend: React (via CDN), Tailwind CSS (via CDN)

Language: JavaScript (ES6+) with JSX

Transpiler: Babel (via CDN)

Backend (Simulated): Browser localStorage acts as a mock database and mongodb.

Planned Full Stack: MERN (MongoDB, Express.js, React, Node.js)

📁 Project Folder Structure
The entire application is self-contained within a single file for maximum portability and ease of use, eliminating the need for complex builds or installations.

index.html # Contains all HTML, CSS, and JavaScript (React) code.

🚀 Setup Instructions
Prerequisites

A modern web browser (e.g., Google Chrome, Firefox)

Visual Studio Code (or any code editor)

The Live Server extension for VS Code is highly recommended.

Installation

Save the complete application code as index.html on your local machine.

No npm install or other package manager steps are required.

🖥️ Running the Application
Open the project folder in Visual Studio Code.

Right-click on the index.html file.

Select "Open with Live Server".

The application will open in your default browser. The URL will typically be (https://g.co/gemini/share/3567a288bdc0) or a similar local address.

🔒 Authentication
Username and password-based authentication.

User session is maintained in localStorage, allowing users to stay logged in between browser sessions on the same device.

📋 API Endpoints (Simulated)
The application uses browser localStorage to simulate a backend API.
| Method | Simulated Endpoint | Description |
| :--- | :--- | :--- |
| POST | /api/users/register | Creates a new user object and saves it to localStorage. |
| POST | /api/users/login | Validates user credentials against localStorage. |
| GET | /api/restaurants | Retrieves restaurant data from a mock object in the code. |
| POST | /api/orders | Creates a new order and saves it to the user's history in localStorage. |

🖥️ User Interfaces
Login & Registration Modal

User Profile Page

Restaurant Listing Page with Filters

Restaurant Menu Page

Shopping Cart Modal

Checkout Flow (Address & Payment)

Order Confirmation & History Pages

🧪 Testing
Frontend: Manually tested across modern browsers using Google Chrome DevTools for UI consistency, responsiveness, and functionality.

User Flows: Tested end-to-end user journeys, including signup, login, logout, adding items to the cart, and completing a mock order. Verified that user data (profile, order history) persists correctly.

👨‍💻 Team Members
Team Leader: Dhannodi Hemanth Kumar

Team member: Dandu Keerthi

Team member: Shaik Topivali

Team member: Yakasi Keerthi

Team member: Leela Siddu

🎥 Demo
The live, interactive application generated from the index.html file serves as the project's primary demo.

📌 Note
This project is a comprehensive frontend prototype designed for academic and learning purposes, focusing on core React concepts, state management, and responsive design within a single-file architecture.
