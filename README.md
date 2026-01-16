# 🗂️ Task Tracker

A simple, browser-based task tracking application inspired by JIRA-style workflows, built with React and Tailwind CSS.  
The app allows users to manage tasks through a backlog and active board, assign tasks to team members, and safely manage task deletion — with all data persisted locally in the browser.

🔗 **Live Demo:**  
https://777tim777.github.io/TaskTracker/

---

## ✨ Features

- **JIRA-style workflow**
  - Backlog for future work
  - To Do, In Progress, and Done columns for active tasks
- Create, edit, and delete tasks
- **Delete confirmation** to prevent accidental data loss
- **Task assignment** (Unassigned, Tim, JJ)
- Priority levels (Low, Medium, High)
- Persistent storage using **LocalStorage**
- Responsive layout using **Tailwind CSS**
- No backend or build step required

---

## 🛠️ Tech Stack

- **React 17 (UMD via CDN)**
- **Tailwind CSS (CDN)**
- **JavaScript (ES6+)**
- **HTML5**
- **Browser LocalStorage**

This project is intentionally implemented without a build system to keep it lightweight, transparent, and easy to deploy on GitHub Pages.

---

## 🚀 Deployment

The application is deployed using **GitHub Pages**.

### How it’s deployed:
- The project consists of a single `index.html` file
- React and Tailwind are loaded via CDN
- GitHub Pages serves the app directly from the repository

---

## 🧪 Running Locally

No installation required.

1. Clone the repository:
   ```bash
   git clone https://github.com/777tim777/TaskTracker.git
   ```
2. Open `index.html` in your browser  
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
- Apply safe UX patterns (confirmation for destructive actions)
- Understand client-side state management
- Deploy a working web app using GitHub Pages
- Incrementally evolve features based on real user feedback

---

## 👤 Author

**Tim Eybers**  
Junior Developer / IT Specialist  
📍 South Africa  

- GitHub: https://github.com/777tim777  
- LinkedIn: https://www.linkedin.com/in/timeybers/
