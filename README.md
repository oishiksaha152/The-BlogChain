# 📝 The Blog–Chain

A full-stack **Blog Application** built with **React (frontend)**, **Express (backend)**, and **MongoDB**.  
Features include user authentication, secure file uploads, and CRUD operations for blog posts.

🌍 **Live Demo:** [The Blog–Chain](https://the-blog-chain.vercel.app)

---

## ✨ Features

- 🔐 User registration & login
- 📝 Create, read, update, delete posts
- 🖼️ Image/file uploads
- 🔑 JWT-based authentication
- 📱 Responsive UI (React)
- ⚡ RESTful API backend (Express + MongoDB)

---

## 🚀 Live Deployment

- **Frontend:** Vercel  
  URL → [https://the-blog-chain.vercel.app](https://the-blog-chain.vercel.app)

- **Backend:** Render  
  URL → [https://the-blogchain.onrender.com](https://the-blogchain.onrender.com)

---

## 🛠️ Tech Stack

| Layer       | Technology                |
|-------------|---------------------------|
| Frontend    | React (CRA / Vite)        |
| Backend     | Node.js, Express          |
| Database    | MongoDB + Mongoose        |
| File Upload | express-fileupload        |
| Auth        | JWT (JSON Web Tokens)     |
| Deployment  | Vercel (frontend) & Render (backend) |

---

## ⚙️ Environment Variables

### Frontend (Vercel → Project Settings → Environment Variables)

| Key                     | Value                                           |
|-------------------------|-------------------------------------------------|
| `REACT_APP_BASE_URL`     | `https://the-blogchain.onrender.com/api`       |
| `REACT_APP_ASSETS_URL`   | `https://the-blogchain.onrender.com`           |

---

### Backend (Render → Environment tab)

```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
