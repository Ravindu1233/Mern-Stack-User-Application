# Full Stack Authentication Application

This project is a full-stack application that implements a secure authentication system with the following features:

## Features
- **User Authentication**: Users can register, log in, and update their profiles.
- **JWT Token-Based Authentication**: Secure login and authentication using JSON Web Tokens (JWT).
- **Email Verification**: Password reset functionality with email verification and OTP (One Time Password).
- **Password Recovery**: Users can reset their passwords securely by receiving a verification email.
- **Protected Routes**: Implemented middleware to protect routes that require authentication.
- **User Profile Management**: Update user details after authentication.
- **Form Validation**: Integrated Formik for form handling and validation.

## Backend
- **Node.js & Express**: Backend built using Node.js and Express framework.
- **MongoDB**: Database connection with MongoDB Atlas for storing user data and handling authentication flow.

## Endpoints
- **`/register`**: Register a new user.
- **`/login`**: Log in with JWT token generation.
- **`/getUser`**: Fetch user profile details.
- **`/updateUser`**: Update user information.
- **`/resetPassword`**: Reset password with email OTP verification.

## Frontend
- **React.js**: Frontend built using React with state management using Zustand.
- **Tailwind CSS**: Styled with Tailwind for modern and responsive design.
- **Custom Hooks**: Leveraged custom hooks for reusing functionality across components.
- **Formik**: Used for form handling and validation.

## Technologies Used
- Node.js
- Express
- MongoDB (Atlas)
- JWT for authentication
- React.js
- Formik
- Tailwind CSS
- Axios for API requests

## Project Setup

1. Clone the repository:
   ```bash
   git clone <REMOTE_URL>

