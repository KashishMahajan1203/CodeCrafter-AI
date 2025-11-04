# 🤖 AI Component Generator

An **AI-powered Frontend Component Generator** built with **ReactJS, Vite, TailwindCSS, and Google Gemini API**, designed to create customizable UI components instantly.
This application converts **natural language prompts** into fully functional code snippets using HTML, CSS, Tailwind, Bootstrap, or JavaScript — and lets you **preview, copy, and export** components seamlessly.


---

## 🚀 Features

### ✨ Smart Component Generation

* Define your component prompt and select desired stack:

  * `HTML + CSS`
  * `HTML + Tailwind`
  * `HTML + Bootstrap`
  * `HTML + CSS + JS`
  * `HTML + Tailwind + Bootstrap`
* AI instantly generates production-ready frontend code.

### 🧩 Live Code Editing

* Integrated **Monaco Editor** for instant syntax highlighting and editing.
* Modify, preview, and tweak generated code directly in the browser.

### 🧭 Smooth UI/UX

* Built with **ShadCN UI** and **React Select** for elegant user interaction.
* Includes responsive design, gradient backgrounds, and modern UI themes.

### 🔄 Real-Time Preview

* Code rendered in real time via **Google Gemini API**.
* Supports exporting and clipboard copying for easy deployment.

---

## ⚙️ Dependencies to Install

```bash
# 1️⃣ Vite React App Setup
npm create vite@latest

# 2️⃣ Routing & Icons
npm i react-router-dom react-icons

# 3️⃣ Styling & Gradients
npm install -D tailwindcss@3.4.17
# Use gradientify.codes for gradient ideas

# 4️⃣ UI Components
npm i shadcn-ui
npm i react-select

# 5️⃣ Code Editor
npm i @monaco-editor/react

# 6️⃣ Google Gemini API
npm install @google/generative-ai

# 7️⃣ Loading & Notifications
npm i react-spinners
npm i react-toastify

# 8️⃣ Clipboard Utility
# JavaScript Navigator API for copy to clipboard
```

---

## 🛠️ Tech Stack

**Frontend:**

* ⚛️ React + Vite
* 🎨 TailwindCSS / ShadCN UI
* 🧭 React Router DOM
* 🧩 Monaco Editor
* 🌈 React Icons & Gradients
* 🔮 Google Gemini API (for AI generation)

---

## 📂 Project Structure

```
📦 ai-component-generator
 ┣ 📂 src
 ┃ ┣ 📂 components      # 🧱 Reusable UI components
 ┃ ┣ 📂 pages           # 📄 Main app pages & previews
 ┃ ┣ 📂 editor          # ✏️ Monaco editor logic
 ┃ ┣ 📂 api             # 🔮 Gemini API integration
 ┃ ┣ 📂 utils           # ⚙️ Helper functions
 ┃ ┣ 📜 App.jsx         # 🚀 Root component
 ┃ ┗ 📜 main.jsx        # 🔑 Vite entry file
 ┣ 📜 package.json
 ┣ 📜 tailwind.config.js
 ┗ 📜 README.md
```

---

## ▶️ Installation & Setup

```bash
# Clone repository
git clone https://github.com/KashishMahajan1203/CodeCrafter-AI.git
cd ai-comp-gen

# Install dependencies
npm install

# Run development server
npm run dev
```

---

## 📸 Screenshots

### 🧠 Prompt Input

![AI prompt and stack selection view](https://res.cloudinary.com/dfacldueh/image/upload/v1762273546/Screenshot_2025-11-04_215214_ltfl9k.png)


### 🧩 Code Preview

![Monaco editor with live rendered output]()

### ⚙️ Gemini Integration

![AI-generated code rendered dynamically]()


---

## 📑 Future Enhancements

* 🧠 Multi-model AI support (Gemini, GPT, Claude)
* 🌐 Export to CodeSandbox or StackBlitz
* 💾 Cloud storage for saved components
* 🧱 Component marketplace for sharing UIs
* ⚡ AI-based style consistency checks

---

## 📞 Contact

For queries or collaboration opportunities, reach out via:

* **Email:** [kashishmahajan878@gmail.com](kashishmahajan878@gmail.com)
* **LinkedIn:** [https://www.linkedin.com/in/kashish-mahajan-0591ba2b4/](https://www.linkedin.com/in/kashish-mahajan-0591ba2b4/)
* **GitHub:** [https://github.com/KashishMahajan1203](https://github.com/KashishMahajan1203)

---

*Developed with 💡 and passion by **Kashish Mahajan***
