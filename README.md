# 🤖 SREAgents - Streamline IT Operations Effortlessly

[![Download Latest Release](https://img.shields.io/badge/Download-SREAgents-blue?style=for-the-badge)](https://github.com/tareksyria/SREAgents/releases)

## 📖 What is SREAgents?

SREAgents is a smart assistant platform designed to help manage IT operations. It uses Claude Agent SDK to let you create digital helpers called Agents. These Agents can perform tasks like monitoring system health, tracking performance, and running scheduled checks. You talk to these Agents in everyday language and they carry out your commands.

---

## ✨ Key Features

- Create and control multiple IT operation Agents.
- Set up Agents with specific abilities like monitoring and tracing.
- Talk naturally with Agents to handle tasks.
- View monitoring and tracking data easily.
- Schedule automatic checks using simple or complex timers.

---

## 🎯 Who Is This For?

If you manage IT systems or want a simple way to keep an eye on your servers and apps, SREAgents can help. You don’t need to code or learn complex tools. Just set up the Agents, give them skills, and start talking to them.

---

## 📥 Download & Install

To get started, you need to **visit the release page** and download the latest package for your system.

[Download SREAgents Releases](https://github.com/tareksyria/SREAgents/releases)

---

### Step 1: Visit the Releases Page

Go to the [SREAgents Releases](https://github.com/tareksyria/SREAgents/releases) page. Here, you will find the latest version of the application packaged for different operating systems.

---

### Step 2: Choose Your Download

Pick the file that matches your computer:

- For Windows: Look for `.exe` or `.zip` files.
- For macOS: Look for `.dmg` or `.zip` files.
- For Linux: Look for `.tar.gz` or `.AppImage` files.

Download the file to your computer.

---

### Step 3: Run the Application

Once downloaded, open the file:

- On Windows or macOS, double-click the file and follow prompts to install or run directly.
- On Linux, extract the files and run the executable inside.

---

### Step 4: Follow Simple Startup Instructions

After launching, follow on-screen setup steps to create your first Agent and start managing tasks.

---

## 🚀 Quick Start Guide

SREAgents includes both a frontend (user interface) and a backend (logic and data). You can start both quickly on your computer if you prefer running from source.

### Environment Needed

- **Node.js 18 or newer** – runs the front-end interface.
- **Python 3.10 or newer** – powers the back-end services.
- **uv package manager** – manages Python dependencies.

---

### One-Click Start (Recommended)

Open a terminal or command prompt, navigate to the folder where you saved SREAgents, and run:

```bash
./start.sh
```

This script starts both frontend and backend automatically.

---

### Manual Start

If you want to start frontend and backend separately, follow these steps:

1. **Start Frontend**

   Open terminal or command prompt, go to the `frontend` folder, and run:

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

   The frontend runs at `http://localhost:5173`.

2. **Start Backend**

   Open another terminal window, navigate to the `backend` folder, and run:

   ```bash
   cd backend
   uv run server.py
   ```

   The backend listens on port `8000`.

---

### Access the App

Open your web browser and visit:

```
http://localhost:5173
```

You should see the SREAgents interface, where you can create and manage your Agents.

---

## 🖼️ Screenshots

Here is a preview of the app interface:

**Agent List**

![Agent List](image/1.png)

**Agent Conversation**

![Agent Conversation](image/2.png)

---

## 🗂 Project Structure Overview

Understanding the folders can help if you want to explore or customize:

```
.
├── frontend/          # React + Vite frontend code
│   ├── src/
│   │   ├── components/   # UI components
│   │   ├── context/      # React state contexts
│   │   └── pages/        # App pages
│   ├── package.json
│   └── vite.config.js
├── backend/           # Python FastAPI backend services
│   ├── .claude/
│   │   └── skills/       # Agent skills definitions
│   ├── agents/           # Agent configurations
│   ├── server.py         # Main backend server (port 8000)
│   ├── mock_otel.py      # Mock telemetry server (port 9090)
│   └── pyproject.toml
└── start.sh           # One-step start script
```

---

## ⚙️ How to Create Agents and Assign Skills

1. Use the web interface to create a new Agent.
2. Choose skills like system monitoring or performance tracing.
3. Save your Agent.
4. Use natural language messages in the chat window to ask your Agent to run tasks.

Agents act like helpers that can monitor your systems or gather important data without extra coding.

---

## 🛠 Troubleshooting

- If the frontend does not load, check if Node.js is installed.
- If backend fails, verify Python version and dependencies.
- Use the `start.sh` script if you want a quick setup without handling commands.
- Check your firewall to allow ports 5173 and 8000.

---

## 🔗 Useful Links

- [SREAgents Releases](https://github.com/tareksyria/SREAgents/releases)
- [Claude Agent SDK Documentation](https://claude.ai/docs) *(for advanced users)*
- [Node.js Download](https://nodejs.org/)
- [Python Download](https://python.org/)

---

Feel free to download and try SREAgents using the button below:

[![Download on GitHub](https://img.shields.io/badge/Download-SREAgents-blue?style=for-the-badge)](https://github.com/tareksyria/SREAgents/releases)