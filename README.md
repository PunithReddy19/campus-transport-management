# Campus Transport Management System

A backend system for managing campus transportation, including routes, stops, vehicles, schedules, authentication, role-based access control, and live vehicle GPS locations.

## Features

- User registration and login
- Password hashing using bcrypt
- JWT authentication
- HTTP-only cookie authentication
- Protected API routes
- USER and ADMIN role-based access control
- Route management
- Stop management with GPS coordinates
- Vehicle management
- Live vehicle location tracking
- Schedule management
- Request validation
- Centralized error handling
- MongoDB database integration
- RESTful API architecture

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- express-validator
- cookie-parser
- Postman

## Project Structure

```text
campus-transport-management/
│
├── controllers/
│   ├── authController.js
│   ├── userController.js
│   ├── routeController.js
│   ├── stopController.js
│   ├── vehicleController.js
│   └── scheduleController.js
│
├── middleware/
│   ├── authMiddleware.js
│   ├── roleMiddleware.js
│   └── errorMiddleware.js
│
├── models/
│   ├── User.js
│   ├── Route.js
│   ├── Stop.js
│   ├── Vehicle.js
│   └── Schedule.js
│
├── routes/
│   ├── authRoutes.js
│   ├── userRoutes.js
│   ├── routeRoutes.js
│   ├── stopRoutes.js
│   ├── vehicleRoutes.js
│   └── scheduleRoutes.js
│
├── validators/
│   └── routeValidator.js
│
├── server.js
├── package.json
├── package-lock.json
├── .env
└── .gitignore