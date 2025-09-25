# Real-Time Chat & Project Collaboration App

A full-stack application for **real-time chat, project collaboration, and AI-assisted tasks**.  
This project allows users to create projects, collaborate with team members, chat in real-time, manage files, and even use AI to assist in tasks and coding.

---

## 📝 Project Definition

This app enables multiple users to work together on projects with real-time updates. Key functionalities include:  

- User authentication & authorization  
- Project creation, collaboration & management  
- Real-time messaging using **Socket.IO**  
- AI integration for task assistance & code suggestions  
- File tree structure & code editor for project files  
- Run projects in a web container environment  
- Prompt engineering for AI responses  

---

## ⚡ Features

- **User Authentication:** Login, register, logout with Redis session management  
- **Project Management:** Create projects, add collaborators, view project details  
- **Real-Time Messaging:** Chat with collaborators inside projects  
- **AI Assistance:** GPT-based AI for task help and prompt-based responses  
- **File Management:** File tree, code editor with syntax highlighting  
- **Run Projects:** Execute code in a web container within the app  

---

## 🛠️ Technology Stack

**Backend:**  
- Node.js + Express  
- MongoDB / Mongoose  
- Redis for session management  
- Socket.IO for real-time communication  
- AI Integration (Gemini API / OpenAI)  

**Frontend:**  
- React + Vite  
- React Router DOM  
- Context API for state management  
- Code editor integration (Monaco / custom editor)  

---

## 🚀 Setup Instructions

1. Clone the repository:
```bash
git clone <repo-url>
cd <project-folder>
````

2. Install backend dependencies:

```bash
cd backend
npm install
```

3. Setup `.env` file with:

```
MONGO_URI=<your-mongodb-uri>
REDIS_URL=<your-redis-url>
AI_API_KEY=<your-ai-key>
```

4. Run backend server:

```bash
npm run dev
```

5. Install frontend dependencies:

```bash
cd frontend
npm install
npm run dev
```

6. Open browser at `http://localhost:5173`

---

