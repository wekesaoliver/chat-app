# Chat App using MERN Stack & Socket.io

## 📌 Overview
This is a real-time chat application built using the **MERN Stack (MongoDB, Express, React, Node.js)** and **Socket.io**. The app allows users to join chat rooms and communicate instantly with others. It supports multiple users, real-time message updates, and user notifications.

## 🚀 Features
- 🔄 **Real-time messaging** with WebSockets
- 👥 **Multi-user support** in chat rooms
- 🎨 **Responsive UI** built with React
- 🛠️ **Easy setup and deployment**
- 🏷️ **User notifications** for new messages
- 🔒 **User authentication (JWT-based)**

## 🛠️ Technologies Used
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Real-time Communication:** Socket.io

## 📂 Project Structure
```
chat-app/
│── client/  (React Frontend)
│   ├── src/
│   ├── public/
│   ├── package.json
│
│── server/  (Node.js Backend)
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── config/
│   ├── server.js
│
│── package.json
│── README.md
```

## ⚡ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/wekesaoliver/chat-app.git
cd chat-app
```

### 2️⃣ Install Dependencies
#### Backend
```sh
cd server
npm install
```

#### Frontend
```sh
cd client
npm install
```

### 3️⃣ Run the Application
#### Start Backend
```sh
cd server
npm start
```

#### Start Frontend
```sh
cd client
npm start
```

### 4️⃣ Open in Browser
Go to: `http://localhost:3000`

## 🔗 How It Works
1. **User registers/logs in** – JWT authentication is used.
2. **User connects** – When a user opens the app, they join a chat room.
3. **Real-time chat** – Messages are sent and received instantly using Socket.io.
4. **Disconnection handling** – Users are notified when someone leaves.

## 🛠️ Future Improvements
- ✅ Image & file sharing
- 📞 Voice & video call integration
- 📌 Message history & storage

## 📜 License
This project is licensed under the **MIT License**.

## 🙌 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📞 Contact
For any inquiries, reach out to: [your-email@example.com](mailto:your-email@example.com)

---

Enjoy chatting! 🎉

