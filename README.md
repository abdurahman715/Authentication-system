# Authentication System (MERN Stack)

A full-stack authentication system built using the MERN stack with secure authentication, email verification, and password recovery features.

## Live Demo

Deployed on Render: **https://authentication-system-frontend-new.onrender.com**

## Features

* User Signup and Login
* Secure Password Hashing using bcrypt
* JWT-based Authentication
* Welcome Email after signup
* Email Verification using OTP
* Password Reset using OTP
* Protected Routes
* Toast Notifications using React Toastify

## Tech Stack

### Frontend

* React.js
* React Toastify
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* bcrypt
* JWT
* Nodemailer

## Authentication Flow

1. User registers with email and password
2. Password is hashed using bcrypt
3. Welcome email is sent to registered email
4. OTP is generated for email verification
5. User verifies account using OTP
6. User logs in and receives JWT token
7. Forgot password sends OTP
8. Password reset completed securely

## Security Features

* Password hashing using bcrypt
* JWT authentication
* OTP verification
* Protected backend routes

## Deployment

* Frontend deployed on Render
* Backend deployed on Render

## Installation

```bash id="3pk7ui"
git clone <repository-link>
cd authentication-system
```

Install frontend dependencies:

```bash id="8nqz83"
cd client
npm install
```

Install backend dependencies:

```bash id="oc2oy5"
cd server
npm install
```

## Environment Variables

Create `.env` in backend:

```env id="j1dngf"
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
SMTP_USER=your_email
SMTP_PASS=your_password
```

## Run Project

Backend:

```bash id="srlfih"
npm run server
```

Frontend:

```bash id="5uwbnd"
npm run dev
```

## Future Improvements

* Google OAuth Login
* Refresh Token Authentication
* User Profile Dashboard

## Author

Developed by Abdurahman
