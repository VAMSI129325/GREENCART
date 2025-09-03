# GreenCart | MERN E-Commerce Project

Greencart is a full-stack e-commerce web application built using the MERN stack. It features a modern UI developed with React, state management handled via Redux, and secure server-side operations powered by Express & Node.js with JWT authentication. The database is managed using MongoDB for seamless product and user data handling.




# Home Page
![image alt](https://github.com/VAMSI129325/GREENCART/blob/86d6a99f9290529577e8db507a66167693be941b/Screenshot%202025-08-24%20140800.jpg)

![image alt](https://github.com/VAMSI129325/GREENCART/blob/6dfac773e303bff0ff12bc139a7031b1831879d3/Screenshot%202025-08-24%20140819.jpg)

# All Products 
![image alt](https://github.com/VAMSI129325/GREENCART/blob/4949deaed8d22c0ae3f64f274a7fb59d29378c85/Screenshot%202025-08-24%20140842.jpg)
# product Information 
![image alt](https://github.com/VAMSI129325/GREENCART/blob/9538a4d644b82581a7e917a5497118c045e60da2/Screenshot%202025-08-24%20140919.jpg)
# Payment Page
![image alt](https://github.com/VAMSI129325/GREENCART/blob/5de8f017133b8753ba75dba3d90def1844ba651e/Screenshot%202025-08-24%20141006.jpg)

# Project Structure

Greencart/
│
├── backend/                  # Server-side (Node.js + Express)
│   ├── config/               # Configuration files (DB, JWT, etc.)
│   │   └── db.js             # MongoDB connection
│   │   └── jwt.js            # JWT auth setup
│   │
│   ├── controllers/          # Business logic (Products, Users, Orders)
│   │   └── productController.js
│   │   └── userController.js
│   │   └── orderController.js
│   │
│   ├── models/               # MongoDB Models (Schemas)
│   │   └── Product.js
│   │   └── User.js
│   │   └── Order.js
│   │
│   ├── routes/               # Express Routes (API endpoints)
│   │   └── productRoutes.js
│   │   └── userRoutes.js
│   │   └── orderRoutes.js
│   │
│   ├── middleware/           # Custom middleware
│   │   └── authMiddleware.js
│   │   └── errorMiddleware.js
│   │
│   ├── utils/                # Helper functions (payment, validators)
│   │
│   ├── server.js             # Entry point for backend
│   └── package.json
│
├── frontend/                 # Client-side (React + Redux)
│   ├── public/               # Static assets
│   ├── src/
│   │   ├── components/       # Reusable UI components (Navbar, Footer, etc.)
│   │   ├── pages/            # Page components (Home, Cart, Checkout, etc.)
│   │   ├── features/         # Redux slices (products, cart, user, orders)
│   │   ├── services/         # API calls (axios)
│   │   ├── App.js            # Main App component
│   │   ├── store.js          # Redux store configuration
│   │   └── index.js          # React entry point
│   └── package.json
│
├── .env                      # Environment variables (Mongo URI, JWT secret, etc.)
├── .gitignore
├── README.md
└── package.json              # Root package file (if using concurrently)
