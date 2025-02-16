# Video Call & Online Meeting App (MERN Stack)

## Overview
This is a **Video Call & Online Meeting Application** built using the **MERN (MongoDB, Express, React, Node.js) stack**. The application allows users to create, join, and manage video conferences in real-time.

## Features
- **User Authentication** (Sign Up, Login, Logout)
- **One-on-One & Group Video Calls**
- **Screen Sharing**
- **Chat Messaging** (During calls)
- **Meeting Scheduling & Invitations**
- **Mute/Unmute Audio & Video**
- **Waiting Room & Admin Controls**
- **Responsive UI for Mobile & Desktop**

## Tech Stack
- **Frontend**: React.js, Redux, WebRTC, Socket.io, TailwindCSS
- **Backend**: Node.js, Express.js, WebRTC, Socket.io
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: JWT (JSON Web Token)
- **Cloud Services**: Firebase/Cloudinary (for storing meeting recordings or images)
- **Hosting**: Vercel/Netlify for frontend, AWS/Heroku for backend

## Installation
### Prerequisites
- Node.js & npm
- MongoDB

### Setup Instructions
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo/video-call-app.git
   cd video-call-app
   ```

2. **Install dependencies**:
   ```sh
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. **Set up environment variables** (Create a `.env` file in the backend directory):
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   FRONTEND_URL=http://localhost:3000
   ```

4. **Start the backend server**:
   ```sh
   cd backend
   npm start
   ```

5. **Start the frontend server**:
   ```sh
   cd frontend
   npm start
   ```

6. **Open the application**: Go to `http://localhost:3000` in your browser.

## Usage
- **Sign up/Login** to the application.
- **Create a new meeting** and share the meeting link.
- **Join an existing meeting** using the meeting link.
- **Use features like chat, screen sharing, and video/audio controls.**

## Folder Structure
```
video-call-app/
│── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── App.js
│   ├── public/
│   ├── package.json
│── README.md
```

## Contributing
Feel free to submit pull requests, report bugs, or suggest improvements.

VivekNarayanJHA


