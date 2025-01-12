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


📂 Folder Structure:
----------------------------------
/client
|-- /src
|   |-- /components
|   |   |-- ChatContainer.js
|   |   |-- ChatList.js
|   |   |-- InputText.js
|   |   |-- UserLogin.js
|   |-- /assets
|   |-- App.js
|   |-- App.css
|   |-- Main.js
|   |-- Main.css
|   |-- Index.js
|   |-- Index.css
|-- /public
|-- index.js

/server
|-- App.js
|-- Db.js
|-- /models
|   |-- Chat.js
----------------------------------


🚀 Usage:
----------------------------------
1. Clone the repository:
   git clone https://github.com/kaushlesh79/Qwikchat.git

2. Install dependencies:
   cd backend && npm install
   cd ../frontend && npm install

3. Configure MongoDB in backend/.env:
   MONGO_URI=mongodb://localhost:27017/chatapp

4. Run the servers:
   Backend: cd backend && node app.js
   Frontend: cd frontend && npm start
----------------------------------

📊 Database Schema (MongoDB):
----------------------------------
Collection: messages
| Field       | Type      | Description                          |
|-------------|-----------|--------------------------------------|
| username    | String    | User who sent the message.           |
| message     | String    | The message content.                 |
----------------------------------

⚙️  Key Functionality:
----------------------------------
1. WebSocket Communication:
   - Backend: Handles connections and broadcasts messages via Socket.IO.
   - Frontend: Establishes WebSocket connection for real-time updates.

2. Real-Time Messaging:
   - Messages sent via WebSocket and displayed instantly.

3. Chat History:
   - Persistent storage in MongoDB; fetched upon user connection.
----------------------------------

📱 Responsive Design:
----------------------------------
1. Mobile View:
   - Touch-friendly elements.
2. Desktop View:
   - Spacious layout for better readability.
----------------------------------

🔮 Future Enhancements:
----------------------------------
1. User Authentication:
   - Add secure login using JWT or OAuth.

2. Typing Indicators:
   - Show when users are typing in real-time.

3. File Sharing:
   - Allow users to send images and files.

4. Group Chats:
   - Enable users to create or join group chats.
----------------------------------
EOF


