# 🚀 QuickAI — AI SaaS Platform (PERN Stack)

QuickAI is a production-ready full stack AI SaaS application built using the PERN stack (PostgreSQL, Express.js, React.js, and Node.js).
It enables users to access multiple AI-powered tools such as content generation, resume analysis, and image editing. All integrated under a seamless subscription-based platform.

🔗 **Live Demo:** https://quick-ai-zone.vercel.app

---

## ✨ Key Features

    ⚙️ Core Functionality
      🔐 User Authentication — Secure login, signup, and profile management using Clerk
      💳 Subscription Billing — Premium AI features unlocked through paid subscriptions
      🧠 AI Tool Integration — Multi-feature AI utilities for users and professionals
      🗄️ PostgreSQL Database — Hosted via Neon, a modern serverless PostgreSQL solution
      ⚡ Full Stack PERN Architecture — Combines PostgreSQL, Express, React, and Node for optimal scalability

---

## 🤖 AI-Powered Tools

| Feature | Description |
|----------|--------------|
| 📝 **Article Generator** | Generate AI-written articles from a title and desired length |
| 💡 **Blog Title Generator** | Suggests creative blog titles using keywords and categories |
| 🖼️ **Image Generator** | Creates AI-generated images from user prompts |
| 🪄 **Background Remover** | Removes image backgrounds and returns transparent outputs |
| 🎯 **Object Remover** | Detects and removes specific objects from uploaded images |
| 📄 **Resume Analyzer** | Provides AI-driven feedback and suggestions on uploaded resumes |

---

## 🧰 **Tech Stack**

  **Frontend:** React.js, Tailwind CSS  
  **Backend:** Node.js, Express.js  
  **Database:** PostgreSQL (Neon)  
  **AI Services:** Integrated AI APIs for image & text generation  
  **Authentication:** Clerk  
  **Deployment:** Vercel (Frontend + Backend)

---

**🗂️ Project Structure Overview**

  Client
  
    client/
    │
    ├── public/              # Static files
    ├── src/
    │   ├── assets/          # Images and icons
    │   ├── components/      # Reusable UI components
    │   ├── pages/           # Application pages
    │   ├── App.jsx          # Root app component
    │   ├── main.jsx         # Entry point
    │   └── index.css        # Global styles
    ├── package.json
    └── vite.config.js

  Server
  
    server/
    │
    ├── configs/             # Configuration files
    ├── controllers/         # Business logic
    ├── middlewares/         # Auth and validation middleware
    ├── routes/              # API route definitions
    ├── server.js            # Express app entry
    └── vercel.js            # Serverless deployment config

---

## ⚙️ **Installation & Setup**

1. **Clone the repository**
   ```bash
   git clone https://github.com/samith-shashika/QuickAI
   cd QuickAI
   
2. **Install dependencies**

    npm install
  
3. **Set up environment variables**
   
  Create a .env file and include:

    DATABASE_URL=your_neon_postgres_url
    CLERK_API_KEY=your_clerk_api_key
    AI_API_KEY=your_ai_service_api_key
    
4. **Run development servers**

    Backend
   
       cd server
       npm run dev

    Frontend
   
        cd client
        npm start

---

**🌍 Deployment**

  * Frontend: Vercel
  * Backend: Vercel
  * Database: Neon PostgreSQL
  
---
  
**📜 License**

  This project is licensed under the MIT License.

---
  
**🙌 Credits**

  Developed by Samith Shashika, combining AI + SaaS to empower intelligent productivity apps.
  
  Built with ❤️ using the PERN Stack.
