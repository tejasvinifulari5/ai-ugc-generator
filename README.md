# AI UGC Generator SaaS

<div align="center">

![React](https://img.shields.io/badge/React-Frontend-blue?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql)
![Gemini AI](https://img.shields.io/badge/Gemini-AI-orange?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)

### AI-Powered SaaS Platform for Generating High-Converting UGC Advertisements

</div>

---

## 📌 Overview

AI UGC Generator is a modern full-stack SaaS platform that uses Gemini AI to generate high-quality UGC (User Generated Content) advertisements, marketing scripts, promotional captions, and short-form ad content.

The platform is designed for:
- Content creators
- Startups
- Digital marketers
- E-commerce brands
- Social media agencies

Users can generate engaging marketing content for platforms like:
- Instagram Reels
- YouTube Shorts
- TikTok
- Facebook Ads
- Pinterest

---

# ✨ Features

## 🔥 Core Features

- AI-generated UGC advertisements
- Marketing script generation
- Responsive modern UI
- Secure authentication
- User dashboard
- Real-time AI response generation
- PostgreSQL database integration
- REST API architecture

---

## 🤖 AI Features

- Gemini AI integration
- Smart prompt generation
- Ad copy generation
- Marketing caption generation
- Product-based content generation

---

## 🔐 Authentication & Security

- Clerk Authentication
- Protected routes
- JWT-based authentication flow
- Secure API handling
- Environment variable protection

---

## 📊 SaaS Features

- Dashboard system
- User-specific content history
- Scalable backend architecture
- API-driven workflow

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Tailwind CSS
- Axios
- React Router DOM

## Backend
- Node.js
- Express.js

## Database
- PostgreSQL
- Neon Database

## Authentication
- Clerk

## AI Integration
- Gemini API

## Monitoring
- Sentry

## Deployment
- Vercel
- VPS / Render / Railway

---

# 📂 Project Structure

```bash
ai-ugc-generator/
│
├── client/                     # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/                     # Node.js backend
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── models/
│   └── package.json
│
├── screenshots/                # Project screenshots
├── docs/                       # Documentation
├── README.md
├── .gitignore
└── LICENSE
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-ugc-generator.git
cd ai-ugc-generator
```

---

## 2️⃣ Setup Frontend

```bash
cd client
npm install
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

## 3️⃣ Setup Backend

Open another terminal:

```bash
cd server
npm install
npm start
```

Backend runs on:

```bash
http://localhost:5000
```

---

# 🔑 Environment Variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000

DATABASE_URL=your_database_url

GEMINI_API_KEY=your_gemini_api_key

CLERK_SECRET_KEY=your_clerk_secret_key

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

# 🧠 System Workflow

```text
User Input
   ↓
Frontend Request
   ↓
Backend API
   ↓
Gemini AI Processing
   ↓
Generated UGC Content
   ↓
Database Storage
   ↓
Dashboard Display
```

---

# 📸 Screenshots

## Dashboard
Add screenshot here:

```md
![Dashboard](./screenshots/dashboard.png)
```

---

## AI Generation Page

```md
![Generation](./screenshots/generation.png)
```

---

## Authentication

```md
![Auth](./screenshots/auth.png)
```

---

# 🚀 Deployment

## Frontend Deployment

Deploy frontend using:
- Vercel
- Netlify

---

## Backend Deployment

Deploy backend using:
- VPS
- Railway
- Render

---

## Database

Use:
- Neon PostgreSQL

---

# 📡 API Endpoints

## Generate UGC Content

```http
POST /api/generate
```

### Request Body

```json
{
  "product": "Wireless Earbuds",
  "targetAudience": "Students",
  "platform": "Instagram"
}
```

---

## Get User History

```http
GET /api/history
```

---

# 🧪 API Testing

Recommended tools:
- Postman
- Thunder Client

---

# 📈 Future Improvements

- Multi-platform ad generation
- AI engagement prediction
- Analytics dashboard
- Subscription & credits system
- AI thumbnail generation
- Team collaboration
- Multi-language support
- Export generated content
- Video storyboard generation

---

# 🎯 Learning Outcomes

This project demonstrates:

- Full-stack web development
- REST API development
- AI integration
- Authentication systems
- PostgreSQL database management
- SaaS architecture
- Deployment workflows
- Modern UI/UX implementation

---

# 🔒 Security Best Practices

- Protected environment variables
- Secure authentication
- Backend route protection
- Database security practices
- API validation

---

# 📚 Documentation

Additional documentation can be added inside the `/docs` folder.

Example:
- API documentation
- Architecture diagrams
- Deployment guide

---

# 🤝 Contributing

Contributions are welcome.

## Steps

### 1. Fork the repository

### 2. Create a new branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Commit your changes

```bash
git commit -m "feat: add new feature"
```

### 4. Push your branch

```bash
git push origin feature/your-feature-name
```

### 5. Open a Pull Request

---

# 👨‍💻 Author

## Tejasvini Fulari

---

# 🌟 Show Your Support

If you found this project useful:

⭐ Star this repository  
🍴 Fork this repository  
📢 Share this project  

---

<div align="center">

### Built with ❤️ using React, Node.js, PostgreSQL, and Gemini AI

</div>
