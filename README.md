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

## 📸 Screenshots 

### 1️⃣ หน้าเว็บ Task Board
<img width="1897" height="861" alt="image" src="https://github.com/user-attachments/assets/213fd820-248b-4abc-9b6c-5fdf3f60aebf" />

### 2️⃣ ALL Tasks
<img width="1893" height="863" alt="image" src="https://github.com/user-attachments/assets/4f6695e6-61b5-4f2d-b597-a50e044dbfb7" />


## 📚 Technologies Used
- **Backend:** Node.js + Express.js  
- **Database:** SQLite  
- **Frontend:** HTML, CSS, JavaScript  
- **Tools:** npm, Git, VS Code  



