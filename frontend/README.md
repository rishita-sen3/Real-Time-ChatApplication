# Real-Time Chat Application 💬

A full-stack real-time chat application built with **Node.js, Express, Redis, Socket.IO, and React**.  
It allows users to join chat rooms, send and receive messages instantly, and manage chat history.

---------------------------------------------------------------------------------------

## 🚀 Features
- Real-time messaging with Socket.IO
- Join chat rooms with unique IDs
- Display online/offline status of users
- Chat history storage with Redis
- Scalable backend with Express
- React frontend with routing & context
- Clean UI with modern components

---------------------------------------------------------------------------------------

## 🛠 Tech Stack
**Frontend:**
- React (Vite + React Router)
- Context API for state management
- Axios for API requests
- TailwindCSS / ShadCN UI (if used) for styling

**Backend:**
- Node.js + Express.js
- Socket.IO for real-time communication
- Redis for message storage / pub-sub
- Morgan for logging
- dotenv for environment variables

---------------------------------------------------------------------------------------

## 📂 Project Structure
```

Real-Time-ChatApplication/
│── backend/
│   ├── db/            # Database/Redis connection
│   ├── routes/        # Express routes
│   ├── server.js      # Main backend server
│   └── package.json   # Backend dependencies
│
│── frontend/
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── context/    # User/Chat context
│   │   ├── routes/     # React Router routes
│   │   └── App.jsx     # Main React App
│   └── package.json    # Frontend dependencies
│
│── README.md          # Project documentation

````

---------------------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/rishita-sen3/Real-Time-ChatApplication.git
cd Real-Time-ChatApplication
````

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside `backend/` with:

```env
PORT=5000
REDIS_URL=redis://localhost:6379
```

Run backend:

```bash
npm start
```

--------------------------------------------------------------------------------------

### 3. Setup Frontend

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

The frontend will run on:
👉 `http://localhost:5173`

The backend will run on:
👉 `http://localhost:5000`

---------------------------------------------------------------------------------------

## 🔮 Future Improvements

* User authentication (login/signup with JWT)
* Persistent message storage in MongoDB
* Private chat between two users
* Typing indicators, read receipts
* File/image sharing

---------------------------------------------------------------------------------------

## 👩‍💻 Author

**Rishita Sen**
📌 [GitHub](https://github.com/rishita-sen3)

```

