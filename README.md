<div align="center">

# 🚀 Fullstack Dev Guide

**An interactive, beginner-friendly reference for learning and revising essential fullstack web development concepts.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Site-2ea44f?style=for-the-badge&logo=githubpages&logoColor=white)](https://samnihasnath.github.io/FullStack-dev-Guide-App/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#-tech-stack)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#-tech-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#-tech-stack)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](#-cicd-deployment)

[Live Demo](https://samnihasnath.github.io/FullStack-dev-Guide-App/) · [Report a Bug](https://github.com/SamniHasnath/FullStack-dev-Guide-App/issues) · [Request a Feature](https://github.com/SamniHasnath/FullStack-dev-Guide-App/issues)

</div>

---

## 📖 About

**Fullstack Dev Guide** is a lightweight educational web app that helps students and beginner developers **learn, revise, and track** core fullstack concepts — all in one place.

It covers **Frontend, Backend, Databases, APIs, DevOps, and Developer Tools**, and is built entirely with **HTML, CSS, and Vanilla JavaScript** — no frameworks, no build step, no dependencies.

<p align="center">
  <img src="https://github.com/user-attachments/assets/cbc445ce-9da0-419f-bf93-9d3be97ece5b" alt="Fullstack Dev Guide preview" width="100%">
</p>

---

## 📑 Table of Contents

- [Why This Project?](#-why-this-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [How It Works](#-how-it-works)
- [Topics Covered](#-topics-covered)
- [CI/CD Deployment](#-cicd-deployment)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [What I Learned](#-what-i-learned)
- [Contact](#-contact)

---

## 🎯 Why This Project?

Learning fullstack development means juggling dozens of technologies, and notes often end up scattered across tabs, docs, and videos.

This guide brings everything into **one interactive reference** where you can:

- 📚 Learn key concepts step by step
- 🔍 Find any topic instantly
- 🧠 Revise quickly before exams or interviews
- ✅ Mark topics as learned and track progress
- 🔗 Discover how concepts connect to each other

---

## ✨ Features

| Feature | Description |
| --- | --- |
| 🔍 **Smart Search** | Instantly search across all concepts |
| 🏷️ **Category Filtering** | Narrow topics down by category |
| 📖 **Multi-Tab Learning** | Explore each concept through organized tabs |
| ✅ **Mark as Learned** | Flag concepts you've completed |
| 📊 **Progress Tracking** | See your overall progress at a glance |
| 🔗 **Related Concepts** | Jump between connected topics |
| ⬅️➡️ **Topic Navigation** | Move to the previous/next concept without returning to the list |
| 📱 **Responsive Design** | Works smoothly on desktop, tablet, and mobile |
| ⚡ **Zero Dependencies** | Pure HTML, CSS, and JavaScript |

---

## 🛠️ Tech Stack

| Technology | Purpose |
| --- | --- |
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, layout, responsiveness, and themes |
| **JavaScript (ES6+)** | Application logic and interactivity |
| **Tabler Icons** | UI icons |
| **Git & GitHub** | Version control and source hosting |
| **GitHub Actions** | Automated deployment workflow |
| **GitHub Pages** | Static site hosting |

---

## ▶️ Getting Started

No installation or build tools required.

```bash
# 1. Clone the repository
git clone https://github.com/SamniHasnath/FullStack-dev-Guide-App.git

# 2. Move into the project folder
cd FullStack-dev-Guide-App
```

Then simply open `index.html` in your browser.

> 💡 **Tip:** For auto-reload while editing, use the **Live Server** extension in VS Code.

---

## 📁 Project Structure

```text
FullStack-dev-Guide-App/
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages deployment workflow
├── css/
│   ├── style.css           # Base layout and component styles
│   ├── colors.css          # Color variables
│   ├── themes.css          # Theme definitions
│   ├── animations.css      # Keyframes and transitions
│   └── interactions.css    # Hover, focus, and active states
├── js/
│   ├── app.js              # Application logic
│   └── data.js             # Concept content
├── index.html              # Main page
└── README.md
```

---

## 🧩 How It Works

```text
                     index.html
                         │
          ┌──────────────┴──────────────┐
          ▼                             ▼
      CSS Layer                  JavaScript Layer
   (style · colors ·          ┌────────┴────────┐
    themes · animations ·     ▼                 ▼
    interactions)          data.js           app.js
                        (concept content)  (logic & UI)
                                              │
                         ┌────────────────────┼────────────────────┐
                         ▼                    ▼                    ▼
                      Search              Filtering             Progress
                         └────────────────────┼────────────────────┘
                                              ▼
                                         Learning UI
```

- **`js/data.js`** — stores the content for every concept.
- **`js/app.js`** — handles searching, filtering, concept selection, navigation, related topics, and progress tracking.
- **`index.html`** — defines the interface structure.
- **`css/`** — split by responsibility so styles stay easy to find and maintain.

---

## 📚 Topics Covered

<table>
<tr>
<td valign="top" width="33%">

**🎨 Frontend**
- HTML & CSS
- JavaScript & the DOM
- Responsive Design
- Web APIs
- Frontend Architecture

</td>
<td valign="top" width="33%">

**⚙️ Backend**
- Servers & HTTP
- REST APIs & CRUD
- Middleware
- Authentication & Authorization
- Backend Architecture

</td>
<td valign="top" width="33%">

**🗄️ Databases**
- SQL, MySQL, PostgreSQL
- Database Design
- Relationships
- Indexing
- Transactions

</td>
</tr>
<tr>
<td valign="top">

**🔌 APIs**
- REST & HTTP Methods
- JSON
- Requests & Responses
- Status Codes
- API Authentication

</td>
<td valign="top">

**🚀 DevOps**
- Git & GitHub
- CI/CD
- GitHub Actions
- Deployment
- Environment Variables

</td>
<td valign="top">

**🛠️ Developer Tools**
- VS Code
- Postman
- Browser DevTools
- Terminal

</td>
</tr>
</table>

---

## 🔄 CI/CD Deployment

The site is deployed automatically to **GitHub Pages** using **GitHub Actions** (`.github/workflows/deploy.yml`). Every push to the repository triggers the workflow and publishes the latest version.

```text
Code changes → git push → GitHub Actions → GitHub Pages → 🌐 Live site
```

To publish an update:

```bash
git add .
git commit -m "Describe your change"
git push
```

🔗 **Live site:** https://samnihasnath.github.io/FullStack-dev-Guide-App/

---
## 🤝 Contributing

Contributions are welcome — new concepts, UI improvements, and bug fixes all help!

1. **Fork** the repository on GitHub
2. **Clone** your fork
   ```bash
   git clone https://github.com/<your-username>/FullStack-dev-Guide-App.git
   ```
3. **Create** a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Commit** your changes
   ```bash
   git add .
   git commit -m "Add: short description of your change"
   ```
5. **Push** to your fork
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open a Pull Request** describing what you changed and why

---

## 💡 What I Learned

Building this project gave me hands-on experience with:

- **Frontend fundamentals** — semantic HTML, modular CSS architecture, responsive design
- **JavaScript** — DOM manipulation, event handling, dynamic rendering, search & filtering
- **State management** — tracking UI state and local learning progress without a framework
- **Project organization** — separating data, logic, and styles cleanly
- **DevOps basics** — Git workflows, GitHub Actions, CI/CD, and GitHub Pages deployment

---

## 📬 Contact

**Samni Hasnath**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samni_Hasnath-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/samni-hasnath03)
[![GitHub](https://img.shields.io/badge/GitHub-SamniHasnath-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/SamniHasnath)

---

<div align="center">

### 🚀 Learn • Practice • Build • Improve

Made with ❤️ for developers learning fullstack engineering

⭐ **If this project helped you, consider giving it a star!**

</div>
