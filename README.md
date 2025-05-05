# ⚡ CodeAssist - AI-Assisted Code Editor with Real-Time Collaboration

> 🎓 Final Year B.Tech Project

**CodeAssist** is a powerful, lightweight, AI-assisted code editor that allows developers to collaborate in real-time while benefiting from AI-driven coding features. Built using modern web technologies and integrated with Google’s Gemini API and Firebase, CodeAssist supports intelligent code suggestions, error detection, documentation generation, and seamless workspace management.

---

## 🚀 Features

- 🔄 **Real-Time Collaboration** – Code with multiple users simultaneously.
- 🤖 **AI Assistance (Google Gemini API)** – Smart code completions, syntax linting, auto-documentation, and correction.
- 💬 **Built-in Chat System** – Communicate with team members in the workspace.
- 👥 **Live Cursor Tracking** – View real-time presence of collaborators.
- 🗂️ **Recursive File Explorer** – Create, rename, delete, and organize files and folders with real-time syncing.
- 🌐 **Cross-Device Syncing** – All edits and messages are instantly reflected across all devices.
- 🔐 **Secure Authentication** – Google OAuth and Email/OTP based login system.

---

## 🧠 Problem Statement

Developers often face the following challenges in collaborative environments:

- No real-time code editing with live team presence.
- Lack of intelligent coding assistance (e.g., linting, suggestions).
- Disorganized workspaces with poor file management.
- Manual saving and frequent merge conflicts.

**CodeAssist** solves these with a unified, smart, and collaborative development platform.

---

## 🧩 Tech Stack

| Area                   | Technology Used                           |
|------------------------|-------------------------------------------|
| Frontend               | Next.js 15, Tailwind CSS, Shadcn UI       |
| Editor                 | Monaco Editor                             |
| Backend                | Firebase Realtime Database & Firestore    |
| Authentication         | Firebase Authentication (Google & OTP)    |
| AI Services            | Google Gemini API                         |
| Programming Language   | JavaScript                                |

---

## 🏗️ Architecture Overview

### 1. 🔐 Authentication & Database
- Google OAuth and Email-based OTP login.
- Password reset and update features.
- Firebase Realtime Database syncs code, files, and user activity live.

### 2. 🤖 AI Integration
- **Smart Suggestions & Linting** – Gemini API provides contextual auto-completion.
- **Documentation Generator** – AI auto-generates helpful function documentation.
- **Code Correction** – Detects and suggests syntax fixes instantly.
- **AI Chatbot** – In-editor chatbot for real-time coding assistance.

### 3. 📝 Code Editor Features
- Multi-language support, theming, and font customization.
- Monaco Editor with collapsible sections and real-time auto-save.

### 4. 🗂️ File Management System
- Recursive file/folder hierarchy with drag-and-drop support.
- Real-time file creation, deletion, and renaming.

### 5. 👥 Collaboration Tools
- Live cursor tracking for every user in a workspace.
- In-app chat and real-time notifications on workspace changes.
- Invite system to add collaborators dynamically.

---

## 🔧 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Abhi13-02/Haxplore.git
cd Haxplore
