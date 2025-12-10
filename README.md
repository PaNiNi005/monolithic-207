# 📋 Task Board - Monolithic Architecture

A simple Task Management System built using **Node.js, Express.js, SQLite, HTML, CSS, and JavaScript** in a **Monolithic Architecture** approach.  
This project is part of ENGSE207 – Software Architecture (Week 3).

---

## ✨ Features
- View all tasks
- Create new task
- Delete task
- REST API (CRUD)
- SQLite database

---

## 🚀 Setup & Run

### 1. Install dependencies
```bash
npm install
2. Start the server
bash
คัดลอกโค้ด
npm start
Server will run at:
👉 http://localhost:3000

📸 Screenshots Checklist (What to Capture for Report)
To complete the lab submission, capture these screenshots:

1️⃣ UI Screenshot (Task Board)
The main webpage

Form for adding tasks

Task list displayed

2️⃣ Server Running (Terminal)
Output after running npm start

Should show:

Server running at http://localhost:3000

Database connected

3️⃣ API Responses
Capture JSON result of:

GET /api/tasks

POST /api/tasks

DELETE /api/tasks/:id

4️⃣ Project Folder Structure
Show folders: public/, database/, and server.js

5️⃣ SQLite Database Output
After running:

bash
คัดลอกโค้ด
sqlite3 database/tasks.db "SELECT * FROM tasks;"
Show inserted sample data + tasks created from UI

🗂️ Project Structure
pgsql
คัดลอกโค้ด
week3-monolithic/
├── server.js
├── package.json
├── database/
│   ├── schema.sql
│   └── tasks.db
├── public/
│   ├── index.html
│   ├── style.css
│   └── app.js
├── .gitignore
└── README.md
📚 Technologies Used
Backend: Node.js + Express.js

Database: SQLite

Frontend: HTML, CSS, JavaScript

Tools: npm, Git, VS Code

