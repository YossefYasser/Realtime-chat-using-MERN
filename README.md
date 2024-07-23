# Realtime Chat using MERN

A simple realtime chat application built using the MERN stack and Socket.io.

## Introduction

This project is a realtime chat application built with the MERN (MongoDB, Express, React, Node.js) stack and Socket.io. It allows users to register, log in, and chat with each other in real time. The application manages user authentication, user status, and message storage efficiently.

## Setup

### Environment Variables

Create a `.env` file with the following variables:
```env
PORT=your_port
MONGO_DB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
NODE_ENV=development
### Running the Project
```
1. Install dependencies:
    ```sh
    npm install
    ```

2. Build the app:
    ```sh
    npm run build
    ```

3. Start the app:
    ```sh
    npm start
    ```

## Endpoints

### Authentication
- **POST /api/auth/register**: Register a new user
- **POST /api/auth/login**: Log in an existing user

### User Management
- **GET /api/users**: Get all users
- **GET /api/users/:id**: Get a user by ID

### Messages
- **GET /api/messages/:chatId**: Get messages from a chat
- **POST /api/messages**: Send a new message

## Thank You

Thank you for checking out this project! If you have any questions or suggestions, feel free to reach out. Contributions are welcome.


