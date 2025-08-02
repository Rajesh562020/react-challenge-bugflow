# 🐞 Bugflows React Login Challenge

This project is a conversion of a static HTML/CSS/JS login page into a modular, component-based React.js application using **Vite** and **CSS Modules**.

## 🚀 Project Setup

Built using:

- ⚛️ React (Functional Components only)
- ⚡ Vite for fast dev environment
- 🎨 CSS Modules for component-scoped styles
- 🔧 useState and onSubmit for form handling

```markdown
## 📁 Folder Structure

```bash

src/
├── components/
│   └── LoginForm.jsx
│   └── LoginForm.module.css
├── App.jsx
├── main.jsx
└── index.css (optional global styles)

````

## 💡 Features

- Clean conversion from static HTML to JSX
- Styles moved into scoped CSS Modules
- Form submission handled via `useState` and `onSubmit`
- On successful login, it triggers an `alert` and logs credentials to console (demo purpose)


## 📦 Getting Started

1. **Clone the repo**

```bash
git clone https://github.com/Rajesh562020/react-challenge-bugflow
cd react-challenge-bugflow
````

2. **Install dependencies**

```bash
npm install
```

3. **Start the dev server**

```bash
npm run dev
```

## 🧪 How It Works

* The login form uses controlled components via `useState`
* On submit, it prevents default behavior and shows a success `alert`
* All components are separated for clean readability and reuse

## 📫 Submission

Submitted as part of the Bugflows React.js Coding Challenge.
Author: **Rajesh Singh**


---

## 📝 License

This project is for educational/demo purposes. No authentication or backend is implemented.
