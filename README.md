# ✅ TaskFlow — React Task Manager App

A clean and functional task manager built with React. Manage your tasks with priority levels, filtering, and persistent storage — all without a backend.

## ✨ Features

- ➕ Add tasks with **High / Medium / Low** priority
- ✅ Mark tasks as complete with a checkbox
- 🔍 Search tasks in real time
- 🔽 Filter by **All / Active / Completed**
- 📊 Progress bar showing overall completion
- 🗑️ Delete individual tasks or clear all completed
- 💾 **localStorage** persistence — tasks survive page refresh
- 📱 Fully responsive layout

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS3-Inline_Styles-1572B6?style=flat&logo=css3&logoColor=white)

- **React 18** (via CDN — no build step required)
- **React Hooks** — `useState`, `useEffect`, `useMemo`, `useCallback`
- **localStorage API** — custom `useLocalStorage` hook
- **Babel Standalone** — in-browser JSX transpilation

## 🚀 Getting Started

No installation or build step required:

```bash
git clone https://github.com/yourusername/task-manager.git
open index.html
```

Just open `index.html` in any modern browser — it works instantly.

## 📁 Project Structure

```
task-manager/
└── index.html    # Full React app (CDN + inline JSX)
```

## 🧠 Key Concepts Demonstrated

- Custom hooks (`useLocalStorage`)
- Controlled components (form inputs)
- Derived state with `useMemo` for filtering & sorting
- Component composition
- Event handling and conditional rendering

## 🎯 Sorting Logic

Tasks are automatically sorted by:
1. Incomplete before completed
2. High → Medium → Low priority within each group

## 📄 License

MIT — free to use and modify.

---

Built with ❤️ by **Yurii Hohol** · Belgium 🇧🇪
