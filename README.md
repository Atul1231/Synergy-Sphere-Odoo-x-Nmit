```
# 🚀 Synergy Sphere  

Synergy Sphere is an advanced **team collaboration platform** designed to boost productivity and streamline teamwork. Built with a modern stack – **React, TypeScript, Vite (frontend)** and **Node.js, Express, MongoDB (backend)** – it empowers teams with real-time collaboration and efficient project management.  

---

## 📂 Project Structure  

```

Team-Sync-main/
├── backend/               # Express + MongoDB backend
│   ├── src/
│   │   ├── controllers/   # Handle API logic
│   │   ├── models/        # Mongoose models
│   │   ├── routes/        # API routes
│   │   ├── services/      # Business logic
│   │   ├── middlewares/   # Request handling middlewares
│   │   └── ...
│   ├── package.json
│   └── ...
│
├── client/                # React + Vite frontend
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── context/       # Global state management
│   │   ├── routes/        # App routes
│   │   ├── pages/         # Application pages
│   │   └── ...
│   ├── package.json
│   └── ...
│
├── package.json           # Root config (optional)
└── ...

````

---

## ⚡ Features  

- ✅ Workspace & Project Management  
- ✅ Task Assignment & Tracking  
- ✅ Member Roles & Permissions  
- ✅ Real-Time Collaboration  
- ✅ Responsive UI with Tailwind CSS  

---

## 🛠️ Tech Stack  

**Frontend**  
- React + TypeScript  
- Vite  
- Tailwind CSS  

**Backend**  
- Node.js + Express  
- MongoDB + Mongoose  
- JWT Authentication  

---

## 🚀 Getting Started  

### 📌 Prerequisites  
- [Node.js](https://nodejs.org/) (v18+)  
- npm or yarn  
- [MongoDB](https://www.mongodb.com/)  

---

### ▶ Backend Setup  

```sh
cd backend
npm install
cp .env.example .env   # configure environment variables
npm run dev            # start backend server
````

🔹 Runs on: `http://localhost:5000`

---

### ▶ Client Setup

```sh
cd client
npm install
cp .env.example .env   # configure environment variables
npm run dev            # start frontend
```

🔹 Runs on: `http://localhost:5173`

---

## 📜 Scripts

* `npm run dev` – Start development server
* `npm run build` – Build production version
* `npm run lint` – Run linter

---

## 🤝 Contributing

1. Fork this repo
2. Create a feature branch → `git checkout -b feature/my-feature`
3. Commit your changes → `git commit -m 'Add my feature'`
4. Push to branch → `git push origin feature/my-feature`
5. Open a Pull Request 🎉

---

## 📄 License

This project is licensed under the **MIT License**.

---

