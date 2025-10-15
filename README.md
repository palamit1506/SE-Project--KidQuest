# 🧩 KidQuest — Life Skills Learning Platform for Children

🚀 **Live Demo:** [https://kidquest.netlify.app/](https://kidquest.netlify.app/)

---

## 📘 Overview

**KidQuest** is an interactive web application designed for children aged **8–14 years** to develop essential life skills through **gamified learning experiences**.  
It helps children build habits in **time management**, **emotional intelligence**, **financial literacy**, **communication**, and **healthy living** — while empowering **parents**, **teachers**, and **admins** with dashboards to monitor progress, assign tasks, and analyze performance.

---

## 👥 User Roles

- 🧒 **Child** – Tracks homework, finances, and habits; interacts with AI mentor; completes psychometric tests.  
- 👩‍👩‍👧 **Parent** – Monitors child’s progress, health, and emotional well-being.  
- 👨‍🏫 **Teacher** – Assigns homework and tracks student development.  
- 🧑‍💼 **Admin** – Manages users, analytics, and overall platform integrity.  

---

## 🌟 Key Features

### 🧠 Learning & Engagement
- 🤖 **AI Chatbot (“Gandalf the Wise”)** – Emotionally supportive virtual mentor using LLM-based responses.  
- 💪 **Health Tracker** – Daily checklist, water intake counter, and streak analytics.  
- 💰 **Finance Tracker** – Record expenses, set saving goals, and visualize progress.  
- 🧩 **Psychometric Tests** – Assess personality traits, emotional intelligence, and strengths.  
- ⏱️ **Task Tracker & Pomodoro Timer** – Manage tasks, focus sessions, and productivity.  
- 🎨 **Doodling Canvas** – Creative module for self-expression and relaxation.  
- 🏅 **Gamification** – XP, stars, achievements, and level progression.  

---

## 🧱 Tech Stack

### ⚙️ Backend
- **Framework:** Flask (Python 3.10+)  
- **Database:** SQLite via Flask-SQLAlchemy ORM  
- **Auth & Security:** JWT-based RBAC, password hashing, secure sessions  
- **AI Integration:** ChatGroq & OpenRouter APIs for chatbot and psychometry  
- **Testing:** Pytest (unit + integration coverage)  

### 💻 Frontend
- **Framework:** Vue 3 + Vite  
- **Design:** Child-friendly UI with animations, responsive layouts, and Chart.js visualizations  
- **Auth:** JWT Bearer Token  
- **Deployment:** Netlify  

---

## 🧪 Testing

Comprehensive **Pytest** suite covering over **17 API modules**, including:
- Authentication, Health Tracker, Finance Tracker  
- Task Management, Psychometry, Notifications  
- Chatbot Sessions, Admin Analytics  

✅ Tests verify API reliability, data validation, and security (RBAC, SQL injection prevention).

---

## 📊 APIs Implemented

| Module | Example Endpoints |
|--------|-------------------|
| **Authentication** | `/api/auth/*` – Register, Login, Profile |
| **Health Tracker** | `/api/health/*` – Tasks, Streaks, Water Log |
| **Tasks & Pomodoro** | `/api/tasks/*` – Task Management, Focus Sessions |
| **Finance Tracker** | `/api/finance/*` – Transactions, Saving Goals |
| **Psychometry** | `/api/psychometry/*` – Adaptive Assessments |
| **Chatbot** | `/api/chat/*` – AI Emotion Chatbot |
| **Admin & Analytics** | `/api/admin/*` – Analytics, User Control |

> 📄 Full **Swagger-compatible YAML** documentation created for all APIs.

---

## 🧩 Project Architecture

- **Frontend–Backend Integration:** RESTful APIs via Flask-CORS  
- **Database Models:** User, ChildProfile, ParentChild, Tasks, Finance, Health, Achievements, Notifications, etc.  
- **AI Services:** Context-aware responses and adaptive psychometric evaluation  
- **Security:** Enforced role-based access and sanitized inputs  

---

## 🚀 How to Run Locally

### 🖥️ Backend (Flask)
```bash
cd backend
python -m venv venv
venv\Scripts\activate  # or source venv/bin/activate
pip install -r requirements.txt
python app.py

```
```
🌐 Frontend (Vue 3)
cd frontend
npm install
npm run dev
```

Open http://localhost:5173

with backend running on http://localhost:5000


### 🧰 Analytics & Admin Features

- 📊 User statistics and demographic dashboards  
- 🔁 Activity tracking and streak monitoring  
- 🔔 Notification management system  
- 🧹 Cascade delete & migration utilities  

---

### 🪲 Issues & Pull Requests

#### ✅ Issues Resolved
- Parent Dashboard: psychometry, doodling, emotional insights  
- Child Dashboard: chatbot response bugs, story builder fixes  
- Admin Dashboard: analytics aggregation issues  

#### 🔧 Merged Pull Requests
1. Enhanced Notification System  
2. Teacher Dashboard Integration  
3. Admin User Management Upgrade  

---

### 📈 Outcome

**KidQuest** bridges **education**, **technology**, and **gamification** to create a fun, safe, and impactful learning experience.

It showcases:
- 🧩 Modular, scalable architecture  
- 🤖 Secure AI-driven interactions  
- 📊 Data analytics for measurable learning outcomes  
- 🚀 Production-ready deployment: [https://kidquest.netlify.app/](https://kidquest.netlify.app/)

---

> 💡 *Built with love and data — empowering children to learn life skills interactively.*

 


