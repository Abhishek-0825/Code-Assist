⚡Code-Assist - AI-Assisted Code Editor with Real-Time Collaboration
🎓 Final Year Project Overview
Code-Assistt (previously called SynapseCode) is my final year B.Tech project, developed to address the growing needs of modern software development teams. It is an AI-assisted, real-time collaborative code editor that combines powerful coding features with intelligent automation. The project emphasizes teamwork, productivity, and intuitive design—perfect for remote collaboration, coding interviews, and team projects.

📌 Problem Statement
In today’s fast-paced development environment, teams often face challenges like:

Limited real-time collaboration when editing code together.

Lack of intelligent code suggestions, leading to longer development cycles.

Disorganized file and workspace structures.

Frequent issues with synchronization and version conflicts.

Code-Assistt solves these challenges by offering a smart, real-time collaborative platform, tailored especially for student teams and early-stage developers.

✅ Project Goals
Enable multiple users to code together in real time.

Offer AI-powered assistance such as code suggestions, linting, and documentation.

Provide instant file syncing and autosaving to avoid data loss.

Maintain a clean and recursive file management system.

Integrate a chat system and live cursor tracking for smooth team communication.

🏗️ Solution Architecture
1. 🔐 Authentication & Database
Firebase Authentication

Users can register using Google Sign-In or Email with OTP verification.

Password recovery and management is handled securely.

Realtime Database

Firebase Realtime Database and Firestore are used to instantly sync all changes—code edits, chats, file updates, and user activities.

2. 🤖 AI Integration (Google Gemini API)
Smart Code Suggestions

Gemini API is integrated to provide intelligent autocompletions and syntax fixes.

Auto-Documentation

Automatically generates comments for complex functions.

Code Correction

Identifies and fixes syntax errors in real time.

AI Chatbot Assistant

An integrated chatbot helps with doubts, coding guidance, and brainstorming.

3. 🧠 Code Editor & UI
Monaco Editor

A powerful editor supporting multiple programming languages, themes, and collapsible code blocks.

File Navigation Panel

Built using recursion to handle nested folders and files.

Supports dynamic actions like renaming, deletion, and drag-and-drop reordering.

Real-Time Collaboration Tools

Live Cursor Tracking: See where other users are editing in real time.

In-Editor Chat: Team members can chat, discuss code, and share snippets instantly.

Workspace Invites: Collaborators can be invited or removed in real time.

🧰 Tech Stack Used
Feature/Module	Technology Used
Frontend Framework	Next.js 15
Styling	Tailwind CSS, Shadcn UI
Code Editor	Monaco Editor
Backend & Database	Firebase Realtime Database + Firestore
Authentication	Firebase Authentication (Google OAuth + Email/OTP)
AI Integration	Google Gemini API
Programming Language	JavaScript

⚙️ Functional Details
Authentication
Supports secure login via Google or Email OTP.

Includes password reset/update functionality.

Real-Time Collaboration
Firebase Realtime Database is used to sync all:

Code edits

File operations

Cursor movements

Chat messages

Snapshot Listeners track real-time changes continuously.

Editor Features
Multi-language syntax highlighting.

User-controlled themes and layout adjustments.

Autosave: Every code change is saved automatically to prevent loss.

File & Folder Management
Recursively rendered file structure using tree data.

Real-time actions like renaming, creation, deletion, and reordering.

AI Features
Real-time code linting and suggestions via Gemini API.

Instant documentation for functions and classes.

Syntax correction and refactoring help.

Integrated chatbot for AI-driven support inside the workspace.
