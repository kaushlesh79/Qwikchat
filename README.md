# Real-Time Chat Application

A real-time chat web application built using **Node.js**, **Express.js**, **React**, **Socket.IO**, and **MongoDB**. This application allows users to connect, chat, and view chat history in real-time. It is designed to work seamlessly on both desktop and mobile devices.

---

## **Features**

- **User Login**: Simple user login functionality (without authentication).
- **Real-Time Messaging**: Send and receive messages instantly using WebSocket communication.
- **Chat History**: Messages are stored in MongoDB for persistence across sessions.
- **Responsive Design**: Optimized for mobile and desktop views.

---

## **Tech Stack**

### **Backend**
- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Framework for building the server.
- **Socket.IO**: Enables real-time, bidirectional communication.
- **MongoDB**: NoSQL database for storing chat history.

### **Frontend**
- **React**: Component-based UI library.
- **CSS**: For styling and responsive design.

---

## **Getting Started**

### **1. Prerequisites**
Ensure you have the following installed:
- **Node.js** (v14+)
- **npm** (Node Package Manager) or **yarn**
- **MongoDB** (local or cloud instance)

---

### **2. Installation**

#### **Clone the Repository**
```bash
git clone https://github.com/kaushlesh79/Qwikchat.git
cd Qwikchat
```

#### **Install Backend Dependencies**
```bash
   cd Server
   npm install
```

#### **Install Frontend Dependencies**
```bash
   cd Client
   npm install
```

### **Set Up MongoDB**
  1. Start your MongoDB server locally or use a cloud database like MongoDB Atlas.
  2. Create a database named chatapp (or any preferred name).
  3. Update the MONGO_URI in backend/.env with your MongoDB connection string
     ```bash
       MONGO_URI=mongodb://localhost:27017/chatapp
     ```
     
### **3. Runnning the application**

###  **Start the Backend Server**
```bash
    cd Server
    node app.js
```

### **Start the Frontend**
```bash
    cd Client
    npm run dev
```


# Folder Structure
echo "📂 Folder Structure:"
echo "----------------------------------"
echo "Backend (/backend):"
echo "|-- server.js         : Main server file for WebSocket and MongoDB."
echo "|-- models/"
echo "   |-- Message.js     : Mongoose schema for chat messages."
echo "|-- routes/           : API endpoints (if any)."
echo "|-- .env              : Environment variables (e.g., MongoDB URI)."
echo ""
echo "Frontend (/frontend):"
echo "|-- src/"
echo "   |-- components/    : Reusable React components."
echo "   |-- App.js         : React app entry point."
echo "|-- public/           : Static assets."
echo ""
echo "----------------------------------"
echo ""

# Usage
echo "🚀 Usage:"
echo "----------------------------------"
echo "1. Clone the repository:"
echo "   git clone https://github.com/your-username/realtime-chat-app.git"
echo ""
echo "2. Install dependencies:"
echo "   cd backend && npm install"
echo "   cd ../frontend && npm install"
echo ""
echo "3. Configure MongoDB in backend/.env:"
echo "   MONGO_URI=mongodb://localhost:27017/chatapp"
echo ""
echo "4. Run the servers:"
echo "   Backend: cd backend && node server.js"
echo "   Frontend: cd frontend && npm start"
echo "----------------------------------"
echo ""

# Database Schema
echo "📊 Database Schema (MongoDB):"
echo "----------------------------------"
echo "Collection: messages"
echo "| Field       | Type      | Description                          |"
echo "|-------------|-----------|--------------------------------------|"
echo "| username    | String    | User who sent the message.           |"
echo "| message     | String    | The message content.                |"
echo "----------------------------------"
echo ""

# Key Functionality
echo "⚙️  Key Functionality:"
echo "----------------------------------"
echo "1. WebSocket Communication:"
echo "   - Backend: Handles connections and broadcasts messages via Socket.IO."
echo "   - Frontend: Establishes WebSocket connection for real-time updates."
echo ""
echo "2. Real-Time Messaging:"
echo "   - Messages sent via WebSocket and displayed instantly."
echo ""
echo "3. Chat History:"
echo "   - Persistent storage in MongoDB; fetched upon user connection."
echo "----------------------------------"
echo ""

# Responsive Design
echo "📱 Responsive Design:"
echo "----------------------------------"
echo "1. Mobile View:"
echo "   - Touch-friendly elements."
echo "2. Desktop View:"
echo "   - Spacious layout for better readability."
echo "----------------------------------"
echo ""

# Future Enhancements
echo "🔮 Future Enhancements:"
echo "----------------------------------"
echo "1. User Authentication:"
echo "   - Add secure login using JWT or OAuth."
echo ""
echo "2. Typing Indicators:"
echo "   - Show when users are typing in real-time."
echo ""
echo "3. File Sharing:"
echo "   - Allow users to send images and files."
echo ""
echo "4. Group Chats:"
echo "   - Enable users to create or join group chats."
echo "----------------------------------"

  


