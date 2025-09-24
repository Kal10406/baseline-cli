# baseline-cli

A lightweight Node.js CLI tool to scan JS, HTML, and CSS files for modern web features and report their **Baseline** support using the official `web-features` dataset.  

This project was built for the **Baseline Tooling Hackathon** to help web developers quickly check if modern web features are safe to use in production, without manually looking through MDN, caniuse.com, or blog posts. It removes the uncertainty and productivity tax by giving instant Baseline feedback.

---

## 🚀 Pain Point Solved

Web developers often hesitate to use new features because it's unclear whether they are fully supported across browsers. Jumping between multiple sources is time-consuming and error-prone.  
**baseline-cli** solves this by scanning your code and instantly reporting **Baseline compatibility** for detected features.

---

## 🧑‍💻 Features

- Detects popular modern web features:
  - Fetch API
  - CSS Grid
  - IntersectionObserver
  - Service Workers
  - Web Animations API
  - WebRTC, WebSocket, and more
- Reports **Baseline compatibility** for each detected feature
- Works on individual files or entire directories
- Simple regex-based scanner (extendable to AST parsing)
- MIT License for permissive open-source use

---

## 🛠️ Tech Stack

- Node.js  
- `web-features` npm package  
- Regex-based scanner for feature detection  
- GitHub repository management  
- MIT License  

---

## 📦 Files

- `check.js` – CLI scanner  
- `demo.html` – demo file containing modern web features  
- `package.json` – project configuration  
- `README.md` – this file  

---

## 💻 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/Kal10406/baseline-cli.git
cd baseline-cli
npm install
