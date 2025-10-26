Product Inventory is a full-stack web application designed for managing products efficiently.
It provides a modern, easy-to-use interface where authenticated users can add, view, search, filter, edit, and delete products in an inventory system — all in real time.

This project demonstrates how to build a complete full-stack app using React, Vite, and Supabase, showcasing the integration of a cloud backend with a responsive, modern frontend.

⚙️ Core Concepts Demonstrated

Building a dynamic frontend using React + Vite

Managing state and UI interactions with React Hooks

Using Supabase as the backend for authentication and database operations

Handling CRUD (Create, Read, Update, Delete) functionality for product records

Implementing search and category-based filtering

Securing user sessions through Supabase Auth

Deploying a production-ready project using Vercel

✨ Key Features

View Products: Display all products as elegant cards showing name, image, price, stock, and category

Add Product: Add new products directly from the UI through a dedicated form

Edit Product: Update existing product details quickly

Delete Product: Remove products securely from the database

Search & Filter: Instantly search or filter products by category (e.g., Clothing, Electronics)

User Authentication: Only logged-in users can access the dashboard (enabled by Supabase Auth)

Responsive Design: Works perfectly across devices with a clean, professional interface built using Tailwind CSS

📸 Screenshot
<img width="1828" height="885" alt="Screenshot 2025-10-25 114658" src="https://github.com/user-attachments/assets/c19327a6-16e2-41f4-ae64-3b60c79daf80" />


🧰 Tech Stack
Frontend

React.js – Component-based UI library

Vite – Fast build tool and dev server

Tailwind CSS – Utility-first CSS framework for styling

TypeScript – Ensures cleaner, type-safe code

Fetch API – For connecting to Supabase APIs

Backend

Supabase – Provides a managed PostgreSQL database, authentication, and real-time APIs

.env configuration – Securely stores database keys and credentials

💡 Why I Used Supabase

I chose Supabase because it provides all backend features I needed without writing custom Node.js or Express code.
It offers:

A ready PostgreSQL database

Built-in authentication

Automatic API endpoints

Real-time synchronization

This allowed me to focus on the frontend functionality and design while still having a robust, scalable backend.

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/Ujwal-kumar-reddy/invento-hub-54.git
cd invento-hub-54

2. Install Dependencies
npm install

3. Configure Environment Variables

Create a .env file in the root directory and add your Supabase credentials:

VITE_SUPABASE_URL=https://your-project.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key

4. Run the Development Server
npm run dev


Your app will open at http://localhost:5173
.

🌐 Deployment

The project is deployed using Vercel, which hosts the React frontend and connects it to the Supabase backend.

Live App:  https://invento-hub-54.vercel.app

📡 Supabase Database Tables
Table	Description
products	Stores product details like name, price, category, image URL, stock
users	Handles authenticated user information
👤 Author

Ujwal Kumar Reddy
GitHub:  https://github.com/Ujwal-kumar-reddy

📄 License

This project is licensed under the MIT License .
