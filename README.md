
# AI Resume Analyzer

## ⚡ Introduction
AI Resume Analyzer is a modern, lightweight web application that helps users analyze and improve their resumes. Upload your PDF or DOCX file, and the app provides keyword extraction, role-specific feedback, and optimization suggestions for ATS (Applicant Tracking Systems). Built with cutting-edge front-end tools and a sleek developer-friendly architecture.

---

## 📋 Table of Contents
- [Introduction](#-introduction)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [License](#-license)

---

## ⚙️ Tech Stack

### 🖥️ Frontend
- **React 19** – Core UI framework
- **React Router 7** – Seamless routing and navigation
- **Zustand** – Global state management
- **Tailwind CSS v4** – Utility-first styling
- **tw-animate-css** – Simple animation utility layer
- **TypeScript** – Type safety and developer tooling

### 🔧 Tooling
- **Vite 6** – Blazing fast dev/build tooling
- **vite-tsconfig-paths** – Simplified TypeScript path aliases
- **@tailwindcss/vite plugin** – Tailwind integration for Vite

---

## 🚀 Features
- Upload and analyze resumes (PDF or DOCX)
- Keyword extraction and ATS scoring suggestions
- Highlight skill gaps based on role
- Clean and responsive UI
- Smooth animations and transitions

---

## 🛠️ Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

**Clone the repo:**
```bash
git clone https://github.com/ZachCortez/ai-resume-analyzer.git
cd ai-resume-analyzer
````

**Install dependencies:**

```bash
npm install
# or
yarn
```

---

## ▶️ Usage

Start the development server:

```bash
npm run dev
# or
yarn dev
```

Navigate to `http://localhost:5173` (or whatever port Vite outputs) to use the app.

---

## 🗂️ Project Structure

```
ai-resume-analyzer/
├── app/                  # Main app components, routes, and logic
├── public/               # Static assets (icons, images, PDF worker)
├── vite.config.ts        # Vite + Tailwind + TS path config
├── tailwind.config.ts    # Tailwind CSS configuration
├── tsconfig.json         # TypeScript config
├── package.json          # Project dependencies
└── README.md             # Project overview
```

---

## 📄 License

Distributed under the [MIT License](LICENSE).

---

💡 **Note:** This project is front-end only for now. If backend AI analysis is required, you can integrate with an API built in Python (Flask/FastAPI) or Node.js, and connect it to this UI via `fetch`/`axios`.

---

