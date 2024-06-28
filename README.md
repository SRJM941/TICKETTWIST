# TicketTwist

TicketTwist is a full-stack web application built to facilitate real-time ticket booking for movies across multiple theatres. It provides separate interfaces for Users, Admins, and Theatre Owners, leveraging MongoDB for robust data storage and management.

## Features

- **User Authentication**: Secure JWT authentication and password hashing using BCrypt.
- **Role-Based Access**: Separate interfaces for Users, Admins, and Theatre Owners.
- **Admin Functions**: Upload movies, manage shows, and approve theatre additions.
- **Theatre Owner Functions**: Add theatres, manage shows with multiple timeslots.
- **Booking Management**: Check seat availability, book tickets securely.
- **Payment Integration**: Stripe payment gateway for secure transactions.
- **State Management**: Redux and Redux Toolkit for efficient state management.
- **UI Components**: Ant Design library with custom stylesheets for enhanced UI.

## Installation

### Prerequisites
- Node.js installed
- MongoDB installed or MongoDB Atlas account

### Clone Repository
```bash
git clone https://github.com/SRJM941/TicketTwist.git
cd TicketTwist

Setup Client
cd client
npm install   # Install client-side dependencies
npm start     # Start the client-side

Setup Server
cd ../server
npm install   # Install server-side dependencies
npm start     # Start the server-side using nodemon app.js
```
## Enviroment Variables
Create a .env file in both client and server folders with the following variables:

### Server env variables
- `mongo_url=YOUR_MONGODB_URL`
- `jwt-secret=YOUR_JWT_SECRET`
- `stripe_key=YOUR_CLIENT_BASE_URL`
- `Port=YOU_SERVER_PORT`

## Dependencies
- `MongoDB, Express, React, Node.js (MERN stack)`
- `Mongoose, React Router, Axios, Stripe`
