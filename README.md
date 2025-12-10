# 📋 Task Board - Monolithic Architecture
## นางสาว รัฐจิกาลณ์ กวงคำ 67543210063-3

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


### 1. Install WSL2 (Windows only – run PowerShell as Admin)
```bash
wsl --install -d Ubuntu-22.04
wsl --set-default-version 2
```

### 2. Update System (inside Ubuntu/WSL)
```bash
sudo apt update && sudo apt upgrade -y
```

### 3. Install Node.js 20
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
```

### 4. Install SQLite
```bash
sudo apt install -y sqlite3
```

### 5. Install Git
```bash
sudo apt install -y git
```

### 6. Verify Installation
```bash
node --version    # Should show v20.x.x
npm --version     # Should show 10.x.x
sqlite3 --version # Should show 3.x.x
git --version     # Should show 2.x.x
```

### 2. Start the server
```bash
npm start
```

Server will run at:  
👉 http://localhost:3000

---

## 📸 Screenshots Checklist (What to Capture)

### 1️⃣ UI Screenshot (Task Board)
Capture:
- Main webpage  
- Add Task form  
- Task list  

### 2️⃣ Server Running (Terminal)
Must show:
- `Server running at http://localhost:3000`
- `Database connected`

### 3️⃣ API Responses (JSON)
Capture response of:
- `GET /api/tasks`
- `POST /api/tasks`
- `DELETE /api/tasks/:id`

### 4️⃣ Project Folder Structure
Show folders:
```
public/
database/
server.js
```

### 5️⃣ SQLite Database Output
Run:
```bash
sqlite3 database/tasks.db "SELECT * FROM tasks;"
```
Capture screenshot of:
- inserted sample data  
- tasks added from UI  

---

## 🗂️ Project Structure
```
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
```

---

## 📚 Technologies Used
- **Backend:** Node.js + Express.js  
- **Database:** SQLite  
- **Frontend:** HTML, CSS, JavaScript  
- **Tools:** npm, Git, VS Code  

