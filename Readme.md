# Advanced Auth (RABC) 🔒



## About This Project

Advanced Auth (RABC) is a comprehensive authentication Project that provides a full-stack setup for user authentication and authorization. It includes both backend and frontend modules, covering essential functionality such as email verification, password reset, and secure session management. This project is ideal for developers looking to implement robust authentication in their applications.

## Features


- 🔧 **Backend Setup** – Initialize backend server, database, and key configurations
- 🗄️ **Database Setup** – Connect MongoDB and manage user data securely
- 🔐 **Signup Endpoint** – Create new user accounts and send verification emails
- 📧 **Sending Verification Email** – Guide users to verify their accounts via email
- 🔍 **Email Verification Endpoint** – Confirm and activate user accounts
- 📄 **Welcome Email Template** – Send a welcome email upon successful verification
- 🚪 **Logout Endpoint** – Manage user sessions effectively
- 🔑 **Login Endpoint** – Authenticate users securely
  - **Account Lockout Feature** – If a user enters the wrong password more than three times, their account will be locked for **15 minutes**. They will see a message:  
    **"Account locked. Try again after [time]."**
- 🔄 **Forgot Password Endpoint** – Allow users to reset forgotten passwords
- 🔁 **Reset Password Endpoint** – Secure password resetting process
- ✔️ **Check Auth Endpoint** – Verify user authentication status
- 🌐 **Frontend Setup** – Develop the UI for all authentication pages
- 📋 **Signup Page UI** – Interface for user registration
- 🔓 **Login Page UI** – Interface for user login
- ✅ **Email Verification Page UI** – Confirm user emails
- 📤 **Implementing Signup** – Integrate signup and verification with the backend
- 📧 **Implementing Email Verification** – Verify emails after signup
- 🔒 **Protecting Routes** – Secure routes based on user authentication
- 🔑 **Implementing Login** – Add login functionality to the frontend
- 🏠 **Dashboard Page** – Display user-specific data after login
- 🔄 **Implementing Forgot Password** – Allow password reset requests
- 🚀 **Detailed Deployment** – Steps to deploy both backend and frontend

## Setup `.env` File

In both `Backend` and `Frontend`, create an `.env` file with the following environment variables:

```plaintext
# Backend .env file
PORT=5000
MONGODB_URL=your_mongo_url
JWT_SECRET=your_jwt_secret
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token
MAILTRAP_ENDPOINT=https://send.api.mailtrap.io/

CLIENT_URL=http://localhost:5173
```

## Running the Project Locally

### 1. Backend Setup

To set up and start the backend server:

```shell
cd Backend
npm install
npm run dev
```

This will start the backend server on `http://localhost:5000`.

### 2. Frontend Setup

To set up and start the frontend application:

```shell
cd Frontend
npm install
npm run dev
```

This will start the frontend on `http://localhost:5173`.


### Building and Starting the App in Production

To build and start the app in production mode:

```shell
npm run build
npm start
```
## More Features Coming Soon

## License

This project is licensed under the [MIT License](LICENSE).

© Darshan Vasani. All Rights Reserved.


