# 🗂️ Task Tracker

A simple, browser-based task tracking application inspired by JIRA-style workflows.  
The app supports a shared task board with a backlog and active workflow, allowing multiple users to collaborate using a common data store.

🔗 **Live Demo:**  
https://777tim777.github.io/TaskTracker/

---

## ✨ Features

- **JIRA-style workflow**
  - Backlog for future work
  - To Do, In Progress, and Done columns
- Create, edit, and delete tasks
- **Delete confirmation** to prevent accidental removal
- **Task assignment** (Unassigned, Tim, JJ)
- Priority levels (Low, Medium, High)
- **Shared storage** using Supabase (tasks visible across devices and users)
- Responsive layout using Tailwind CSS
- No custom backend server required

---

## 🛠️ Tech Stack

- **React 17 (UMD via CDN)**
- **Tailwind CSS (CDN)**
- **Supabase (PostgreSQL + API)**
- **JavaScript (ES6+)**
- **HTML5**

This project is intentionally implemented without a build step to keep it lightweight and easy to deploy on GitHub Pages.

---

## 🚀 Deployment

The frontend is deployed using **GitHub Pages**.

- The application consists of a single `index.html` file
- React, Tailwind, and Supabase are loaded via CDN
- Supabase provides shared persistence via a hosted PostgreSQL database

---

## 🧪 Running Locally

No installation required.

1. Clone the repository:
   ```bash
   git clone https://github.com/777tim777/TaskTracker.git
   ```
2. Open `index.html` directly in your browser  
   **or**
3. Serve it locally (optional):
   ```bash
   npx serve
   ```

---

## 📁 Project Structure

```
TaskTracker/
├── index.html
└── README.md
```

---

## 🎯 Purpose of This Project

This project was created as a **learning and portfolio exercise** to:

- Practice React fundamentals without a build tool
- Implement a realistic, JIRA-inspired task workflow
- Introduce shared state using a backend-as-a-service (Supabase)
- Apply safe UX patterns for destructive actions
- Understand client–server interaction without managing a custom backend
- Deploy a working collaborative web app using GitHub Pages

---

## 👤 Author

**Tim Eybers**  
Junior Developer / IT Specialist  
📍 South Africa  

- GitHub: https://github.com/777tim777  
- LinkedIn: https://www.linkedin.com/in/timeybers/
