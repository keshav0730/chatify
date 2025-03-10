# Realtime Chat App

A real-time chat application built using **React.js, Node.js, Express, and Socket.io**. This app enables instant messaging with real-time updates, user authentication, and a modern UI.

## 🚀 Features

- 🔥 **Real-time messaging** with WebSockets (Socket.io)
- 👤 **User authentication** (JWT-based login/signup)
- 🎨 **Modern UI** built with React & Tailwind CSS
- 🔔 **Typing indicators & online status**
- 🗂 **Chat rooms & direct messages**
- 📱 **Responsive design** for mobile & desktop

## 🛠 Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **WebSockets:** Socket.io
- **Database:** MongoDB (optional for user management)
- **Authentication:** JWT (JSON Web Tokens)

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/realtime-chat.git
cd realtime-chat
```

### 2️⃣ Install Dependencies
#### For Backend:
```sh
cd server
npm install
```

#### For Frontend:
```sh
cd client
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file inside the `server/` folder and add:
```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application
#### Start Backend:
```sh
cd server
npm start
```
#### Start Frontend:
```sh
cd client
npm start
```

## 🚀 Deployment
- Frontend: **Vercel / Netlify**
- Backend: **Render / Railway / AWS / Heroku**

## 🤝 Contributing
Pull requests are welcome! Feel free to open an issue for suggestions.


