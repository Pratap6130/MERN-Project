# MERN Project Website

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue.svg)

## 🚀 Introduction
MERN Amazona is a full-fledged e-commerce web application built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). This project adheres to modern web development practices, offering a fully functional e-commerce platform that includes user authentication, product management, and order processing.

## 🛠 Features

- **User Authentication & Authorisation** (Login, Register, Admin Panel)
- **Product Management** (CRUD operations for products)
- **Shopping Cart** (Add, remove, and update cart items)
- **Order Processing** (Checkout, payment integration, and order history)
- **Admin Dashboard** (Manage products, users, and orders)
- **Responsive Design** (Optimised for mobile and desktop views)
- **Payment Integration** (Stripe/PayPal support for transactions)
- **RESTful API** (Efficient API structure with secure endpoints)

## 📂 Folder Structure
```
mern-amazona-master/
│── backend/          # Node.js & Express Backend API
│── frontend/         # React.js Frontend Application
│── config/           # Configuration files (DB, JWT, etc.)
│── models/           # Database Models (MongoDB Schemas)
│── routes/           # API Routes for different functionalities
│── controllers/      # Logic and Business Layer for API
│── middleware/       # Authentication & Error Handling Middleware
│── utils/            # Helper Functions and Utilities
│── .env.example      # Example Environment Configuration
│── package.json      # Project Dependencies
│── README.md         # Project Documentation
```

## 🏗️ Tech Stack
- **Frontend:** React.js, Redux, React Router, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ORM)
- **Authentication:** JSON Web Tokens (JWT)
- **Payment Gateway:** Stripe / PayPal
- **Deployment:** Vercel / Netlify (Frontend), Heroku / Render (Backend)

## ⚙️ Installation & Setup

1. **Clone the Repository**
```sh
   git clone https://github.com/Pratap6130/mern-amazona-master.git
   cd mern-amazona-master
```

2. **Install Dependencies**
```sh
   cd backend && npm install
   cd ../frontend && npm install
```

3. **Set Up Environment Variables**
   - Rename `.env.example` to `.env`
   - Update the necessary environment variables (MongoDB URI, JWT_SECRET, etc.)

4. **Run the Application**
```sh
   cd backend && npm start
   cd frontend && npm start
```

5. **Access the Application**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000`


## 🚀 Deployment
To deploy the application, you can use services like:
- **Frontend:** Vercel / Netlify
- **Backend:** Heroku / Render
- **Database:** MongoDB Atlas

## 📌 Contributing
Feel free to contribute to this project. If you find any issues or want to add features, follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

Give a ⭐ if you like this project!


