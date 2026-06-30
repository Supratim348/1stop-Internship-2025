# 1Stop Internship 2025 — Web Projects

Three front-end mini-projects built during the 1Stop internship: an **Expense Tracker**, a **Calculator**, and a **To-Do List** (TaskMaster Pro). Each one is a self-contained static site — HTML, CSS, and vanilla JavaScript, styled with Bootstrap.

A combined landing page (`index.html`) is included at the root of this repo so all three tools can be browsed from one place.

## Live Preview

Open [`index.html`](./index.html) in a browser, or enable **GitHub Pages** for this repo (Settings → Pages → deploy from the `main` branch, root folder) and visit:

```
https://<your-username>.github.io/1stop-Internship-2025/
```

## Projects

| # | Project | Folder | Description |
|---|---------|--------|--------------|
| 1 | 💰 Expense Tracker | [`Project-1 Expense Tracker/`](./Project-1%20Expense%20Tracker/index.html) | Log expenses, view running totals, and keep a detailed transaction history. |
| 2 | 🧮 Calculator | [`Project-2 Calculator/`](./Project-2%20Calculator/index.html) | A clean, fully-functional on-screen calculator for everyday arithmetic. |
| 3 | ✅ TaskMaster Pro (To-Do List) | [`Project-3 To Do List/`](./Project-3%20To%20Do%20List/index.html) | Add, complete, and manage daily tasks in a simple to-do list interface. |

## Tech Stack

- HTML5 / CSS3 / vanilla JavaScript
- [Bootstrap](https://getbootstrap.com/) (bundled per-project under each `vendor/` folder)
- Bootstrap Icons (Project 1)
- jQuery (Project 3)

No build step or dependencies to install — every project runs directly in the browser.

## Project Structure

```
1stop-Internship-2025/
├── index.html                     # Combined landing page linking all 3 projects
├── README.md
├── Project-1 Expense Tracker/
│   ├── index.html
│   ├── assets/
│   └── vendor/
├── Project-2 Calculator/
│   ├── index.html
│   ├── assets/
│   └── vendor/
└── Project-3 To Do List/
    ├── index.html
    ├── assets/
    └── vendor/
```

## Running Locally

Clone the repo and open `index.html` directly, or serve it with any static server:

```bash
git clone https://github.com/Supratim348/1stop-Internship-2025.git
cd 1stop-Internship-2025
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## License

For educational/internship purposes.
