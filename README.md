<p align="center">
  <img src="your_logo_link_here" width="200px">
</p>

# 🚀 Chattify - Real-time Chat App

<p align="center">
  <img src="your_gif_here" width="700px">
</p>

<p align="center">
  <a href="your_demo_link_here"><img src="https://img.shields.io/badge/Live%20Demo-Vercel-blue?style=for-the-badge&logo=vercel"></a>
  <img src="https://img.shields.io/badge/React-18.0.0-blue?style=for-the-badge&logo=react">
  <img src="https://img.shields.io/badge/Redux-Toolkit-purple?style=for-the-badge&logo=redux">
  <img src="https://img.shields.io/badge/TailwindCSS-3.0-blue?style=for-the-badge&logo=tailwindcss">
  <img src="https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb">
</p>

## 🌟 Overview
**Chattify** is a modern, real-time chat application built on the **MERN stack**, designed for seamless communication with a sleek and responsive UI.

---

## ✨ Features
✔️ **Real-time messaging** with WebSockets ⚡  
✔️ **Secure authentication** using JWT 🔐  
✔️ **Modern & responsive UI** with TailwindCSS 🎨  
✔️ **Emoji & file sharing support** 📁🎉  
✔️ **Deployed on Vercel** 🚀  

---

## 🎥 Demo Preview
<p align="center">
  <img src="your_demo_gif_here" width="700px">
</p>

---

## 📊 Tech Stack
```mermaid
graph TD;
  React --> Redux;
  React --> TailwindCSS;
  Node.js --> Express;
  Express --> MongoDB;
  Vercel --> Deployment;
```

---

## 🚀 Getting Started
### Prerequisites
- Install **Node.js** and **MongoDB**

### 🔧 Installation
```bash
git clone https://github.com/your-username/chattify.git
cd chattify
npm install
```

### 🚀 Run the Project
```bash
# Start the server
npm run server

# Start the frontend
npm start
```

---

## 🖥️ UI Screenshots
<p align="center">
  <img src="your_screenshot_link_1" width="45%">
  <img src="your_screenshot_link_2" width="45%">
</p>

---

## 🔥 Code Snippet (Real-time Messaging)
```js
const socket = io("https://yourserver.com");

// Sending a message
const sendMessage = (message) => {
  socket.emit("chatMessage", message);
};

// Receiving messages
socket.on("message", (msg) => {
  console.log(msg);
});
```

---

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`feature-awesome-thing`)
3. Commit your changes
4. Create a Pull Request

---

## 📩 Contact & Support
📧 Email: [your-email@example.com](mailto:your-email@example.com)  
💬 LinkedIn: [your-profile](your_profile_link_here)  

---

⭐ **Star this repo if you like it!** ⭐







# ✨ Full Stack Realtime Chat App ✨

Highlights:

- 🌟 Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI
- 🎃 Authentication && Authorization with JWT
- 👾 Real-time messaging with Socket.io
- 🚀 Online user status
- 👌 Global state management with Zustand
- 🐞 Error handling both on the server and on the client

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
