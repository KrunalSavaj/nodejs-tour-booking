# Node.js Tour Booking System

This is a **RESTful API** for a Tour Booking System built with **Node.js, Express, and MongoDB**. It allows users to explore tours, book them, leave reviews, and process payments via **Stripe**. The system includes **JWT authentication, role-based access control, and error handling** to ensure security and efficiency.

## Features
- User authentication (Signup/Login with JWT)
- Role-based access control (Admin, User, Guide)
- Tour management (CRUD operations)
- Booking system with **Stripe Payment Integration**
- Reviews & Ratings for tours
- Secure API with validation and error handling

## Installation

### Clone the Repository
```bash
git clone https://github.com/yourusername/nodejs-tour-booking.git
cd nodejs-tour-booking
```

### Install Dependencies
```bash
npm install
```

### Environment Variables
Create a `.env` file in the root directory and configure the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### Start the Server
#### Development Mode
```bash
npm run dev
```
#### Production Mode
```bash
npm start
```

## API Endpoints
- `POST /api/v1/auth/signup` - Register a new user
- `POST /api/v1/auth/login` - Login user
- `GET /api/v1/tours` - Get all tours
- `POST /api/v1/tours` - Create a new tour (Admin only)
- `POST /api/v1/bookings` - Book a tour
- `POST /api/v1/reviews` - Add a review

## Technologies Used
- Node.js, Express.js
- MongoDB, Mongoose
- JWT Authentication
- Stripe Payment Integration
- RESTful API Design

## License
This project is licensed under the **MIT License**.

---
Made with ❤️ by [KrunalSavaj]

