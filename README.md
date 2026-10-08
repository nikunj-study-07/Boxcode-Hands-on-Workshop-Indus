# 🚀 Boxcode Workshop Guide

Welcome to the **Boxcode Workshop**! This guide will help you install Boxcode CLI & IDE and try out prompts ranging from quick questions and roadmaps to building a full AI web application.

---

## 📥 Installation

### 🖥️ Option 1: Boxcode CLI (Terminal)

#### 1. Install
- **Windows (PowerShell):**
  ```powershell
  irm https://boxcode.sh/install.ps1 | iex
  ```
- **macOS / Linux (Terminal):**
  ```bash
  curl -fsSL https://boxcode.sh/install.sh | bash
  ```

> ⚠️ **Note:** Close your current terminal and open a **NEW** window so the changes take effect.

#### 2. Start & Login
In your terminal, run:
```bash
boxcode
```
Inside Boxcode, run:
```text
/login
```

---

### 💻 Option 2: Boxcode IDE (Desktop Application)

1. Go to [https://boxcode.sh/](https://boxcode.sh/) and click **Download IDE**.
2. Run the downloaded installer and complete setup.
3. Open **Boxcode IDE**, click **Sign in** in the top-right corner.
4. Open any project folder and start prompting!

---

## ⚡ Part 1: Quick Warmup Prompts

Try these simple prompts in Boxcode:

### 🔹 Prompt 1: Weather Check
```text
Hey Boxcode, what is today's typical weather in Ahmedabad? Give me a short 2-line forecast with temperature and condition.
```

### 🔹 Prompt 2: 6-Month DSA + AI/ML Roadmap
```text
Create a structured 6-month learning roadmap for a college student covering DSA (Data Structures & Algorithms in Python/C++) alongside AI/ML fundamentals. Break it down month-by-month with key topics and practice goals.
```

### 🔹 Prompt 3: Terminal Command Helper
```text
How do I check my current working directory and list all hidden files in terminal? Give me the exact commands.
```

### 🔹 Prompt 4: JavaScript Quiz
```text
Give me 3 easy multiple-choice quiz questions on JavaScript basics with the answers at the end.
```

---

## 🎯 Part 2: Main Project — ResearchAI Assistant

### ❓ Step 1: Research Challenges & Problem Analysis

> **Discussion Question:**  
> *When working on academic projects and research papers, what are the biggest hurdles students face in organizing papers, extracting key insights, and collaborating efficiently?*

Paste this prompt in Boxcode:

```text
What are the common problems university students face when conducting academic research and organizing research papers? List 4 key pain points and suggest how a modern web-based AI research assistant tool can solve them.
```

---

### 🛠️ Step 2: Build the ResearchAI Web Application

Paste this master prompt in Boxcode to build the complete solution:

```text
Build a frontend-only React + Tailwind website called "ResearchAI – AI Research Assistant" with a premium, modern university/AI SaaS UI. Include a responsive sidebar, Dashboard, Research Papers with searchable paper cards and details modal, AI Assistant with suggested questions and simulated local AI responses, and Research Insights with attractive insight cards. Use realistic mock data, clean typography, subtle gradients, icons, hover effects, smooth animations, responsive design, and dark mode. Make all frontend interactions functional, fix any console errors, and do not use a backend, database, authentication, or external APIs. Make it look like a polished professional product suitable for a university technology demonstration, not a beginner project.
```
