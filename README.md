# Quick Chat – Fullstack Chat App 

This is a full-stack chat application that enables real-time messaging. The application consists of a backend (Node.js/Express) and a frontend (React). It is deployed and accessible at: [Live Demo](https://fullstack-chat-app-4fep.onrender.com).

## Features
- User authentication (Signup/Login)
- Real-time messaging
- Cloud-based image storage (Cloudinary)
- WebSocket support for instant updates
- Responsive UI

## Technologies Used
### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.io
- Cloudinary API
- JWT Authentication

### Frontend:
- React.js
- Tailwind CSS
- Axios

## Installation & Setup

### Prerequisites:
- Node.js and npm installed
- MongoDB running locally or using a cloud-based service like MongoDB Atlas

### Steps:
```bash
# 1. Clone the repository
git clone https://github.com/YOUR_GITHUB_USERNAME/fullstack-chat-app.git
cd fullstack-chat-app

# 2. Backend Setup
cd backend
npm install
cp .env.example .env  # Add your environment variables
npm start

# 3. Frontend Setup
cd ../frontend
npm install
npm start

# 4. Open the application in the browser
# Navigate to:
http://localhost:3000

