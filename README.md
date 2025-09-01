# 🛡️ The Definitive SQL Injection Experience

An interactive web-based simulation that demonstrates how **SQL Injection (SQLi)** attacks work, why they’re dangerous, and how **parameterized queries** protect against them.

This project is a **learning tool** – it provides a safe, isolated environment to experiment with SQL injection concepts without connecting to a real database.

---

## ✨ Features

* 🎨 **Immersive UI**

  * Aurora background animations
  * Glitchy cyberpunk headers
  * Glassmorphism panels with smooth transitions
  * Scanline + terminal-like effects

* 🧑‍💻 **Attack Simulation**

  * **Authentication Bypass** (`' OR '1'='1' --`)
  * **Data Exfiltration** with `UNION SELECT`
  * **Blind Injection** with `SLEEP()`

* 🔐 **Mode Toggle**

  * **Vulnerable Mode** → Inputs are directly concatenated into queries.
  * **Patched Mode** → Queries are parameterized and immune to injection.

* 📊 **Live Database Viewer**

  * Shows mock tables (`users`, `products`)
  * Highlights rows when exfiltration occurs

* 🎯 **SQL Syntax Highlighting**

  * Keywords, strings, numbers, comments, operators, and injected payloads visually distinguished

* 🧾 **Step-by-Step Explanations**

  * Automatically updates to explain what happens in **Vulnerable** vs **Patched** mode
  * Shows the actual SQL query being "executed"

---

## 🚀 Getting Started

### 1. Clone this repo

```bash
git clone https://github.com/yourusername/sql-injection-experience.git
cd sql-injection-experience
```

### 2. Open in browser

No build tools required. Just open the HTML file:

```bash
open index.html
```

(or double-click it)

---

## 📂 Project Structure

```
.
├── index.html        # Main application
├── tailwind.css      # Handled via CDN
└── README.md         # You're reading it
```

All logic is contained in `index.html` for simplicity. TailwindCSS and Google Fonts are pulled in via CDN.

---

## 📸 Screenshots

### Vulnerable Mode

* Shows how raw user input alters SQL queries.
* Demonstrates authentication bypass, data theft, and blind injection.

### Patched Mode

* Queries are parameterized.
* SQL injection attempts fail.

---

## ⚠️ Disclaimer

This project is for **educational purposes only**.
Do **not** use these techniques on systems you don’t own or have permission to test.

---

## 🧑‍🏫 Learning Objectives

* Understand how insecure query concatenation leads to SQL Injection.
* See the impact of common SQLi attack vectors.
* Learn how **prepared statements / parameterized queries** prevent injection.

---

## 🛠️ Technologies Used

* **HTML5 + TailwindCSS** (UI & styling)
* **Vanilla JavaScript** (simulation logic)
* **Google Fonts (Inter + Fira Code)**
* **SVG Icons**

---

## 🌟 Future Enhancements

* Add **Error-Based SQLi** demo
* Expand to include **Stored Procedures** injection scenarios
* Add "Defensive Coding" best practices panel

---

## 📜 License

MIT License © 2025 \[Your Name]

