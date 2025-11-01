# Real-Time Encrypted Chat Application

## Project Overview
This project is a real-time chat application developed using modern web technologies. It consists of a secure backend server built with Node.js, Express.js, MongoDB, and Socket.IO, and an interactive frontend developed with React, Tailwind CSS, and Vite.

## Directory Structure
```
Real-Time-Chat-Application/
├── README.md
├── package.json
├── backend/
│   ├── server.js
│   ├── controllers/
│   │   ├── auth.controller.js
│   │   ├── message.controller.js
│   │   └── user.controller.js
│   ├── db/
│   │   └── connectToMongoDB.js
│   ├── middleware/
│   │   └── protectRoute.js
│   ├── models/
│   │   ├── conversation.model.js
│   │   ├── message.model.js
│   │   └── user.model.js
│   ├── routes/
│   │   ├── auth.routes.js
│   │   ├── message.routes.js
│   │   └── user.routes.js
│   ├── socket/
│   │   └── socket.js
│   └── utils/
│       └── generateToken.js
└── frontend/
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── tailwind.config.js
    ├── vite.config.js
    └── src/
        ├── App.jsx
        ├── main.jsx
        ├── components/
        ├── context/
        ├── hooks/
        ├── pages/
        ├── utils/
        └── zustand/
```

## Backend

### Technologies Used
- **Node.js & Express.js**: Server and API endpoints
- **MongoDB & Mongoose**: Data persistence
- **JWT**: User authentication and session management
- **Socket.IO**: Real-time communication

### Key Functionalities
- **User Authentication**: Secure signup, login, and logout with JWT token handling.
- **Real-time Messaging**: Implemented using Socket.IO, supporting real-time message exchanges.
- **Resource Monitoring**: Integrated CPU and memory usage monitoring during message encryption and decryption.

### Setup
1. **Clone the repository**:
```bash
git clone https://github.com/ramcharan0308/Real-Time-Chat-Application.git
cd Real-Time-Chat-Application
```
2. **Install Dependencies**:
```bash
npm install
```
3. **Configure Environment Variables**: Create a `.env` file in the backend directory:
```bash
MONGO_DB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```
4. **Run the Backend Server**:
```bash
npm run server
```

## Frontend

### Technologies Used
- **React & JSX**: UI development
- **Tailwind CSS**: UI styling
- **Vite**: Project bundling and serving
- **Zustand**: State management
- **Socket.IO Client**: Real-time data handling

### Key Functionalities
- **Responsive UI**: Developed using React and styled with Tailwind CSS.
- **Context Management**: Managed application state via React context and Zustand.
- **Real-time Updates**: Handled through client-side Socket.IO connections.

### Setup
1. **Navigate to the frontend directory**:
```bash
cd frontend
```
2. **Install Dependencies**:
```bash
npm install
```
3. **Run the Frontend Application**:
```bash
npm run dev
```

## Project Commands
- Start Backend:
```bash
npm run server
```
- Start Frontend:
```bash
cd frontend && npm run dev
```
- Build Frontend:
```bash
npm run build
```

## Security
- Secure cookie management with JWT tokens.

---

## 👤 **Author**
🔹 **Ram Charan**  
📧 **vadthyaramcharan369@gmail.com**  
🔗 **GitHub: [ramcharan0308](https://github.com/ramcharan0308)**  

If you found this project useful, **⭐ Star this repository** and feel free to contribute! 🚀

