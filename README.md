# CallVerse-Universe-of-video-calls

# 📞 VideoCall

It is a full-stack Zoom-like web application that enables real-time video calling and instant messaging between users. Built with modern web technologies such as **WebRTC**, **Socket.IO**, **Express**, and **React**, it provides a seamless communication experience with a clean and responsive UI.

## 🚀 Features

- 🔐 User Authentication (Login/Signup)
- 📹 Real-time video and audio calls using WebRTC
- 💬 Instant messaging with Socket.IO
- 👥 Dynamic meeting rooms with unique URLs
- 🧑‍💻 Peer-to-peer video communication
- 📦 Modular backend structure (MVC architecture)
- 🔒 Environment variables managed securely via `.env`
- Screen-Sharing features

## 🛠️ Tech Stack

**Frontend:**
- React.js
- HTML5, CSS3
- Socket.IO Client

**Backend:**
- Node.js
- Express.js
- Socket.IO
- WebRTC
- MongoDB (via Mongoose)

## 📁 Project Structure

```
Videocall/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── app.js
│   ├── .env
│   ├── package.json
│   └── .gitignore
├── frontend/
│   ├── (React app files)
├── README.md
```

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/videocall.git
cd videocall
```

### 2. Setup Backend

```bash
cd backend
npm install
# Add your environment variables in `.env`
npm start
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

## 🌐 Environment Variables (`.env`)

Create a `.env` file inside the `backend/` folder:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

✅ Make sure `.env` is **listed in `.gitignore** to prevent leaks.
