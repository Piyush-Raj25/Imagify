# 🎨 Imagify – AI Image Generation Platform

Imagify is a **full-stack AI-powered image generation platform** that allows users to generate high-quality AI images from text prompts. The platform integrates the **Clipdrop API** for image generation, **JWT-based authentication** for secure user access, and **Razorpay** for seamless credit purchases.

🔗 **Live Demo:** https://imagify-kohl-tau.vercel.app/

---

## 🚀 Features

- 🎨 AI-powered text-to-image generation using the Clipdrop API
- 🔐 Secure JWT Authentication
- 👤 User Registration & Login
- 💳 Credit-based image generation system
- 💰 Razorpay Payment Gateway Integration
- 📈 Real-time credit management
- ⚡ Responsive UI built with React
- 🔄 RESTful API architecture
- ☁️ Production deployment using Vercel & Render

---

# 🛠️ Tech Stack

## Frontend

- React.js
- React Router
- Axios
- CSS
- Vite

## Backend

- Node.js
- Express.js
- JWT Authentication
- REST APIs

## Database

- MongoDB

## Third-Party Services

- Clipdrop API
- Razorpay Payment Gateway

## Deployment

- Vercel
- Render

---

# 📂 Project Structure

```
Imagify
│
├── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── App.jsx
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Piyush-Raj25/Imagify.git
```

---

## Frontend

```bash
cd client
npm install
npm run dev
```

---

## Backend

```bash
cd server
npm install
npm start
```

---

# 🔑 Environment Variables

Create a `.env` file inside the server folder.

```env
MONGODB_URI=
JWT_SECRET=
CLIPDROP_API_KEY=
RAZORPAY_KEY_ID=
RAZORPAY_SECRET=
```

---

# 📸 Screenshots

## Home Page

<img width="1893" height="913" alt="Screenshot 2026-07-27 170727" src="https://github.com/user-attachments/assets/24e2a71a-2ea2-430e-b7b7-f396ef9041ea" />



---

## Image Generation

> Add screenshot here

---

## Credit Purchase

> Add screenshot here

---

## Generated Image

> Add screenshot here

---

# 🔄 Workflow

```text
User Login
      │
      ▼
JWT Authentication
      │
      ▼
Enter Prompt
      │
      ▼
Backend API
      │
      ▼
Clipdrop API
      │
      ▼
Generated Image
      │
      ▼
Store Credits & History
```

---

# 💡 Challenges Solved

- Secure JWT authentication
- Third-party API integration
- Payment gateway integration
- Credit management
- CORS configuration
- Environment variable management
- Production deployment

---

# 📈 Future Improvements

- Image generation history
- Download & share functionality
- Prompt templates
- Dark mode
- AI image editing
- Admin dashboard
- Image favorites
- Usage analytics

---

# 📚 Key Learnings

- Building scalable REST APIs
- JWT Authentication
- Payment Gateway Integration
- MongoDB Data Modeling
- Production Deployment
- Environment Variable Management
- API Error Handling
- Frontend–Backend Communication

---

# 👨‍💻 Author

**Piyush Raj**

- LinkedIn: https://www.linkedin.com/in/piyush-raj-496642249/
- GitHub: https://github.com/Piyush-Raj25
- LeetCode: https://leetcode.com/u/PiyushRaj25/

---

## ⭐ If you found this project useful, consider giving it a star!
