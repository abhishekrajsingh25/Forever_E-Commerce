# MERN E-commerce Full Stack Project with Admin Panel

This is a full-stack e-commerce web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application includes a fully functional user interface for customers and an admin panel for managing products, orders, and users.

---

## Features

- User authentication (Register, Login, Logout) with JWT
- Browse products with search, filter, and pagination
- Add products to the cart and manage cart items
- Secure checkout process with payment integration (Stripe/Razorpay)
- Order tracking and history
- Fully responsive UI for mobile and desktop users.

## Admin Panel Features:

- Dashboard with an overview of orders
- Manage products (Add, Update, Delete, View)
- Manage orders (View, Update order status)

## Tech Stack

### Frontend:

- React.js (with React Router)
- Tailwind CSS for UI styling
- Axios for API requests

### Backend:

- Node.js with Express.js
- MongoDB with Mongoose (for database management)
- JWT Authentication
- Multer for image uploads
- Stripe / Razorpay integration for payments

### Additional Tools:

- Cloudinary (for product image storage)
- dotenv (for environment variables management)
- Bcrypt.js (for password hashing)
- Cors (for handling cross-origin requests)

## Setup Instructions

### Prerequisites:

- Node.js and npm installed
- MongoDB installed or a cloud MongoDB database (MongoDB Atlas)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/abhishekrajsingh25/MERN-Chat-App.git
   cd MERN-Chat-App
   ```

2. **Install Backend Dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../frontend
   npm install
   ```
   
4. **Install Admin Dependencies**
   ```bash
   cd ../admin
   npm install
   ```

### Running the Application

1. **Start the Backend Server**
   ```bash
   cd backend
   npm run dev
   ```
   The backend server should now be running on `http://localhost:4000`.

2. **Start the Frontend**
   ```bash
   cd ../frontend
   npm run dev
   ```
   The frontend should now be running on `http://localhost:5173`.

3. **Start the Frontend**
   ```bash
   cd ../admin
   npm run dev
   ```
   The frontend should now be running on `http://localhost:5174`.

## Usage

1. Open `http://localhost:5173` in a web browser.
2. Enter a username and choose a room to join.
3. Start chatting in real time with others in the same room.

## Deployment

- The frontend can be deployed using Vercel.
- The backend can be deployed using Vercel.
- The admin can be deployed using Vercel.
- MongoDB can be hosted on MongoDB Atlas.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

---

Feel free to contribute, suggest features, or open issues.

---
