# ❓ DoubtSolver – Peer-to-Peer Learning Platform  

**DoubtSolver** is a **full-stack web application** designed to help students **ask, answer, and resolve doubts** in real time. The platform promotes **collaborative learning**, featuring a **community-driven Q&A module**, **tag-based discovery**, and an **admin panel** for moderation and analytics.  

---

## 🔧 Core Features  

### 📝 Doubt Management (CRUD)  
- Users can **post doubts** with tags, descriptions, and attachments.  
- Other users can **answer, comment, and upvote** solutions.  
- Full **CRUD support** for doubts and answers.  

### 👥 Community Interaction  
- **Tag-based filtering** for subject/topic categorization.  
- **Upvote system** to highlight best answers.  
- **Discussion threads** for collaborative problem-solving.  

### 🛡️ Admin Dashboard  
- **User Management** → View & manage registered users.  
- **Moderation Tools** → Flagged doubts/answers are reviewed by admins.  
- **Analytics Panel** → Track most active users, trending tags, and community activity.  

### 🧠 AI Assistance *(Future Scope)*  
- AI-powered **doubt suggestion & auto-answer recommendations**.  
- Smart tagging of doubts based on content.  

---

## 🛠 Tech Stack  

| Layer        | Technology |
|--------------|------------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend**  | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ORM) |
| **Auth**     | JWT (JSON Web Tokens) |
| **Admin**    | Custom-built dashboard (Analytics & Moderation) |

---

## ⚙️ Installation & Setup  

1. **Clone the Repository**  
```bash
git clone https://github.com/your-username/DoubtSolver.git
cd DoubtSolver
```

2. **Install Dependencies**  
```bash
npm install
```

3. **Configure Environment Variables**  
Create `.env` files for **frontend** and **backend**.  

**Backend (`backend/.env`)**  
```env
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
```

**Frontend (`frontend/.env`)**  
```env
VITE_API_URL=http://localhost:5000
```

4. **Run the Application**  
```bash
# Backend
cd backend
npm run dev

# Frontend
cd frontend
npm run dev
```

---

## 📊 Admin Workflow  

- **Flagged Doubts/Answers** → Sent to moderation queue.  
- **Moderation Actions**:  
  - ✅ Approve → Publishes or restores post.  
  - ❌ Delete → Removes inappropriate content.  

---

## 📈 Analytics (Admin Panel)  
- Active users statistics.  
- Trending tags & topics.  
- Most solved doubts leaderboard.  

---

## 📁 Folder Structure  

```
DoubtSolver/
├── frontend/                # React + Tailwind source
├── backend/                 # Node.js + Express source
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
├── utils/
├── .env
├── package.json
└── README.md
```

---

## 🚀 Future Enhancements  
- 🤖 AI-powered **auto-answer suggestions**.  
- 📩 Email & push notifications.  
- 📌 Doubt bookmarking & personalized feed.  
- 🎯 Gamification → badges, leaderboards, and rewards.  
- ⏱ Real-time chat between users & mentors.  

---

⚡ **DoubtSolver – A collaborative platform that transforms peer-to-peer doubt solving into an engaging and efficient experience.**
