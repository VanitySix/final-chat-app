# Full Stack Realtime Chat App

## Overview

This is a **Full Stack Realtime Chat Application** that allows users to communicate in real-time, powered by the MERN stack (MongoDB, Express, React, Node.js) and enhanced with **Socket.io** for real-time communication. The app is styled with **TailwindCSS** and **Daisy UI**.

---

## Key Features

- **MERN Stack**: MongoDB, Express.js, React.js, Node.js
- **JWT Authentication & Authorization**: Secure user login and registration using JSON Web Tokens (JWT).
- **Real-time Messaging**: Chat in real-time using **Socket.io** for bidirectional communication.
- **Online User Status**: Track and display who is online at any given moment.
- **Global State Management**: Use of **Zustand** for simple and scalable state management.
- **User-friendly UI**: Ultilizing **TailwindCSS** and **Daisy UI** for a seemless experience.

---

## Tech Stack

- **Frontend**:
  - **React.js**
  - **TailwindCSS**
  - **Daisy UI**
  - **Zustand** (state management)
  - **Socket.io Client** (for real-time chat)
- **Backend**:
  - **Node.js**
  - **Express.js**
  - **MongoDB** (for storing user data and chat history)
  - **Socket.io** (for real-time messaging)
  - **JWT Authentication** (for secure login and registration)

---

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
