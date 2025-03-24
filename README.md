# **Quick Chat – AI-Powered Chat App**  

A real-time chat application enhanced with **AI-powered features**, including **GPT-based smart replies** and **AI-generated images** via **DALL-E 3**.  

## **Live Demo**  
🔗 **[Try Quick Chat Live](https://fullstack-chat-app-4fep.onrender.com)**  

## **Features**  
✅ **Real-time Messaging** – Instant chat with WebSocket support.  
✅ **AI-Powered Replies** – Smart responses using GPT.  
✅ **DALL-E Image Generation** – AI-created images in chat.  
✅ **User Authentication** – Secure login with JWT.  
✅ **Cloud Storage** – Store images via Cloudinary.  
✅ **Responsive UI** – Modern and intuitive design.  

## **Tech Stack**  
### Backend:  
- **Node.js** – Backend framework.  
- **Express.js** – API and server management.  
- **MongoDB (Mongoose)** – NoSQL database.  
- **Socket.io** – Real-time communication.  
- **Cloudinary** – Cloud-based image storage.  
- **JWT Authentication** – Secure user login.  

### Frontend:  
- **React.js** – Interactive UI.  
- **Tailwind CSS** – Modern styling.  
- **Axios** – API communication.  
- **OpenAI API** – AI-powered messaging & images.  

## **Installation & Setup**  

### Prerequisites:  
- **Node.js and npm installed**  
- **MongoDB running locally or via MongoDB Atlas**  

### **Steps:**  
    ```sh
    # 1. Clone the repository
    git clone https://github.com/YOUR_GITHUB_USERNAME/fullstack-chat-app.git
    cd fullstack-chat-app
    
    # 2. Backend Setup
    cd backend
    npm install
    cp .env.example .env  # Add your environment variables (JWT_SECRET, OPENAI_API_KEY, CLOUDINARY_KEYS, etc.)
    npm start
    
    # 3. Frontend Setup
    cd ../frontend
    npm install
    npm start
    
    # 4. Open the application in the browser
    # Navigate to:
    http://localhost:3000

### **Deployment**
Easily deploy on Render, Vercel, or any Node.js hosting platform.
 
