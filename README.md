# 🚀 Boxcode Hands-on Workshop Guide

Welcome to the **Boxcode Hands-on Workshop**! This repository contains the complete installation manual for both the **Boxcode CLI** and **Boxcode IDE**, along with interactive workshop warmup prompts and our main project challenge.

---

## 📑 Table of Contents
1. [Boxcode CLI Installation Manual](#-boxcode-cli-installation-manual)
2. [Boxcode IDE Installation Manual (Windows)](#-boxcode-ide-installation-manual-windows)
3. [Part 1: Quick Warmup Prompts](#-part-1-quick-warmup-prompts)
4. [Part 2: Main Project — ResearchAI Assistant](#-part-2-main-project--researchai-assistant)

---

## 🖥️ Boxcode CLI Installation Manual

The **Boxcode CLI** is a terminal coding agent that reads your project files, executes commands, and asks for your approval (`y`/`n`) before making destructive changes. Supported on **Windows**, **macOS**, and **Linux**.

### Step 1: Open the Boxcode Website
Go to [https://boxcode.sh/](https://boxcode.sh/) in your browser.

### Step 2: Choose Your Platform
On the home page, click **Explore the CLI**. Select your operating system tab:
- **macOS · Linux**
- **Windows**

### Step 3: Run the Installation Command

#### 🪟 Windows Users:
1. Open **PowerShell** (Run as Administrator recommended).
2. Paste and run the install command:
   ```powershell
   irm https://boxcode.sh/install.ps1 | iex
   ```
3. The installer downloads the prebuilt binary and adds Boxcode to your `PATH`. You will see `Installation complete!`.

#### 🍎 macOS & 🐧 Linux Users:
1. Open your **Terminal**.
2. Paste and run:
   ```bash
   curl -fsSL https://boxcode.sh/install.sh | bash
   ```
3. Wait for the download and setup to finish.

> ⚠️ **Important:** After installation finishes, close your current terminal and open a **NEW** PowerShell / Terminal window. The updated `PATH` only takes effect in a new session.

---

### Step 4: Launch Boxcode
In your new terminal, type:
```bash
boxcode
```
The Boxcode interactive terminal welcome screen will appear.

---

### Step 5: Sign In & Claim Free Credits
Inside the Boxcode CLI, run:
```text
/login
```
1. Your default browser opens automatically to the Boxcode login page.
2. Sign in with Google or Sign up for an account.
3. Authorize Boxcode.
4. You will be redirected to your dashboard where your **$5 free credits** are activated.
5. Return to the terminal—Boxcode is now linked and ready!

---

### Step 6: (Alternative) Manual Custom Endpoint Setup
If `/login` does not open or complete:
1. On your [boxcode.sh dashboard](https://boxcode.sh/), locate the **CLI / IDE config box** (Endpoint, Model, and API Key).
2. In the Boxcode CLI, run:
   ```text
   /provider
   ```
3. Select **Custom endpoint** and press Enter.
4. Paste the 3 values from your dashboard one by one:
   - **Endpoint URL:** (Value after `BOXCODE_ENDPOINT=`)
   - **Model:** (Configured model)
   - **API Key:** (Your private key)
5. Boxcode confirms the new provider is active.

---

### Step 7: CLI Commands Reference Table

| Command | What It Does |
| :--- | :--- |
| `/login` | Sign in with Google in the browser, or check connection status |
| `/logout` | Clear the local boxcode.sh session and promo key |
| `/provider` | Switch model provider or custom endpoint |
| `/model` | Switch AI models |
| `/plan` | Research and plan first, change nothing until you approve |
| `/init` | Generate a `BOXCODE.md` context file read on every session |
| `Ctrl + P` | Display the full command palette |
| `Ctrl + C` | Exit Boxcode CLI |
| `boxcode --upgrade` | Upgrade existing Boxcode CLI to the latest version |

---

## 💻 Boxcode IDE Installation Manual (Windows)

The **Boxcode IDE** is a full desktop AI development environment designed for project-based coding and visual pair-programming.

### Step 1: Open the Website & Download
1. Open your browser and navigate to [https://boxcode.sh/](https://boxcode.sh/).
2. Click **Download IDE** on the homepage.
3. Scroll to the Windows option and click **Download Windows** (or grab the latest `.exe` directly from the [GitHub Releases](https://github.com/HolboxAI/boxcode-ide/releases/latest)).
4. The setup executable `BoxcodeSetup-x64-<version>.exe` will download.

---

### Step 2: Run Installer & Accept Agreement
1. Open your `Downloads` folder and double-click `BoxcodeSetup-x64-....exe`.
2. Review the License Agreement.
3. Select **"I accept the agreement"** and click **Next**.

---

### Step 3: Select Installation Settings
1. **Destination Location:** Default is `C:\Program Files\Boxcode` (change only if needed).
2. **Additional Tasks:** Check the options to:
   - Create a desktop icon
   - Register Boxcode as an editor for supported file types
   - Add to PATH
3. Click **Install** and allow setup to complete.

---

### Step 4: Launch & Authorize
1. Launch **Boxcode IDE** from the Start Menu or desktop shortcut.
2. In the top-right corner of the IDE, click **Sign in**.
3. Sign in to your Boxcode account in the browser and authorize the IDE.
4. Return to Boxcode IDE—your **$5 free credits** will be active.

---

### Step 5: Start Coding with Boxcode IDE
1. Click **Open Folder...** (or `File > Open Folder`) and select your project workspace.
2. Use the **"Describe what to build"** prompt bar in the AI chat panel to instruct Boxcode.

---

### 📌 IDE Quick Reference Table

| Item | Details |
| :--- | :--- |
| **Website** | [https://boxcode.sh/](https://boxcode.sh/) |
| **Latest Releases** | [GitHub Releases](https://github.com/HolboxAI/boxcode-ide/releases/latest) |
| **Platform** | Windows (macOS & Linux available on website) |
| **Default Install Path** | `C:\Program Files\Boxcode` |
| **Authentication** | Click **Sign in** in the top-right corner |
| **Starter Credits** | $5 free upon sign in |

---

## ⚡ Part 1: Quick Warmup Prompts

Test Boxcode’s speed and capabilities with these quick prompts:

### 🔹 Prompt 1: Local Weather Forecast
```text
Hey Boxcode, what is today's typical weather in Ahmedabad? Give me a short 2-line forecast with temperature and condition.
```

### 🔹 Prompt 2: 6-Month DSA + AI/ML Learning Roadmap
```text
Create a structured 6-month learning roadmap for a college student covering DSA (Data Structures & Algorithms in Python/C++) alongside AI/ML fundamentals. Break it down month-by-month with key topics and practice goals.
```

### 🔹 Prompt 3: Terminal Command Helper
```text
How do I check my current working directory and list all hidden files in terminal? Give me the exact commands.
```

### 🔹 Prompt 4: JavaScript Fundamentals Quiz
```text
Give me 3 easy multiple-choice quiz questions on JavaScript basics with the answers at the end.
```

---

## 🎯 Part 2: Main Project — ResearchAI Assistant

### ❓ Step 1: Research Challenges & Problem Analysis

> **Discussion Question:**  
> *When working on academic projects and research papers, what are the biggest hurdles students face in organizing papers, extracting key insights, and collaborating efficiently?*

Paste this prompt into Boxcode:

```text
What are the common problems university students face when conducting academic research and organizing research papers? List 4 key pain points and suggest how a modern web-based AI research assistant tool can solve them.
```

---

### 🛠️ Step 2: Build the Full ResearchAI SaaS Application

Once Boxcode outlines the problems, paste this master prompt to generate the complete solution:

```text
Build a frontend-only React + Tailwind website called "ResearchAI – AI Research Assistant" with a premium, modern university/AI SaaS UI. Include a responsive sidebar, Dashboard, Research Papers with searchable paper cards and details modal, AI Assistant with suggested questions and simulated local AI responses, and Research Insights with attractive insight cards. Use realistic mock data, clean typography, subtle gradients, icons, hover effects, smooth animations, responsive design, and dark mode. Make all frontend interactions functional, fix any console errors, and do not use a backend, database, authentication, or external APIs. Make it look like a polished professional product suitable for a university technology demonstration, not a beginner project.
```
