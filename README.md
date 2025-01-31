# Chattify - Real-Time Chat Application

![Chattify Banner](https://your-banner-image-url.com)

> **Real-time chat, redefined.** A modern and responsive chat application built with the **MERN** stack, featuring **real-time messaging, authentication, emoji support, and file sharing.**

![GitHub stars](https://img.shields.io/github/stars/yourusername/chattify?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/yourusername/chattify?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/yourusername/chattify?style=for-the-badge)

---

## 🚀 Features

✅ **Real-time messaging** – Powered by WebSockets  
🔐 **Secure authentication** – JWT-based authentication  
📱 **Fully responsive** – Works across all devices  
💾 **File sharing** – Upload and send images, PDFs, and more  
🎨 **Sleek UI** – Built with Tailwind CSS for a modern feel  
😃 **Emoji support** – Express yourself better  

---

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens)

---

## 🎥 Demo

🚀 **Live Demo:** [Chattify](https://chattify.vercel.app/)  
📺 **Video Walkthrough:** [YouTube](https://youtube.com/yourvideo)

---

## 🖼 Screenshots

![Chat UI](https://your-image-url.com)
![File Sharing](https://your-image-url.com)

---

## ⚡ Installation & Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/chattify.git
   cd chattify
   ```
2. **Install dependencies**
   ```sh
   npm install
   ```
3. **Start the development server**
   ```sh
   npm run dev
   ```

---

## 🏗️ Code Snippet (Real-time Messaging)

```javascript
// Real-time messaging with Socket.io
socket.on("sendMessage", (message) => {
  io.to(message.chatId).emit("receiveMessage", message);
});
```

---

## 🔥 Upcoming Features

- ✅ **Voice messages**
- ✅ **Group chat**
- ✅ **Read receipts**

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📬 Contact

💼 **Connect with me:** [LinkedIn](https://linkedin.com/in/yourname) | [Portfolio](https://yourportfolio.com)  
📧 **Email:** your.email@example.com









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
