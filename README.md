# 🤖 AI‑Powered Personal AI Assistant Workflow (n8n)

[![n8n](https://img.shields.io/badge/Built%20with-n8n-FF6A00?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)
[![AI](https://img.shields.io/badge/AI‑Powered-Yes-00C853?style=for-the-badge&logo=google-gemini&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-2962FF?style=for-the-badge)](#)

> **A premium, modular, AI‑driven personal assistant built in n8n — combining web search, calendar, Gmail, notes, expense tracking, and tasks into one unified workflow.**

---

## ✨ Overview

**AI‑Powered Personal Assistant Workflow** is a fully integrated n8n automation designed to behave like a smart executive assistant.  
It interprets natural language requests, routes them to the correct tool, and responds instantly — all inside a single workflow.

Whether it’s scheduling meetings, searching the web, managing Gmail, or tracking expenses, this system handles it end‑to‑end.

---

## 🖼 Workflow Preview
<img width="1703" height="709" alt="Workflow" src="https://github.com/user-attachments/assets/0dce9c20-7bb4-4209-84e6-fd5aa9c1918b" />


<img width="1733" height="674" alt="Workflow(1)" src="https://github.com/user-attachments/assets/f126bb46-0499-4b9b-9ea7-af7ea920036e" />

---

## 🚀 Core Capabilities

✅ **Web Search via SerpAPI**  
✅ **Google Calendar Events (Create / Get / List)**  
✅ **Gmail Read & Send**  
✅ **Expense Tracking via Google Sheets**  
✅ **Google Docs Notes (Create / Read / Update)**  
✅ **Google Tasks (Create / Get)**  
✅ **Memory‑Enabled AI Agent**  
✅ **Multi‑Model Support (Gemini + Mistral)**  

---

## 🧠 Intelligence Layer

The AI Agent is governed by strict execution rules:

- Always use tools for live data.
- Never answer from memory if a tool exists.
- Automatically select correct tool based on intent.
- Uses memory buffer for context continuity.

---

## 🧩 Workflow Architecture

```
Webhook → AI Agent → Tool Selection → Execution → Response
```

**Key AI Tools Integrated**

| Category | Tools |
|---------|------|
| Search | SerpAPI |
| Calendar | Google Calendar Tool (Create / Get / List) |
| Email | Gmail Tool (Read / List / Send) |
| Expenses | Google Sheets Tool (Append / Read) |
| Notes | Google Docs Tool (Create / Read / Update) |
| Tasks | Google Tasks Tool |

---

## 📂 Included Workflow File

- **File:** `PERSONAL  AI ASSISTANT WORKFLOW using n8n.json`

---

## ✅ Example Prompts

```
• Schedule a meeting tomorrow at 10 AM
• What is the USD to INR rate today?
• Email the report to my manager
• Log ₹1200 under Travel expense
• Create a note titled "Client Meeting"
```

---

## 🔐 Requirements

- n8n installed (self‑hosted or cloud)
- Google API credentials for:
  - Calendar
  - Gmail
  - Sheets
  - Docs
  - Tasks
- SerpAPI key

---

## ⚡ Setup Steps

1. Import the JSON workflow into n8n.
2. Connect your Google + SerpAPI credentials.
3. Enable the Webhook node.
4. Execute & test with a prompt.

---

## 📌 Highlights

⭐ **Production‑Ready Workflow Design**  
⭐ **Extensible: Add new tools easily**  
⭐ **Premium UI Layout & Organized Node Groups**  
⭐ **Memory + AI Rule Enforcement**

---

## 🧑‍💻 Author

**Gaurav Singh**  
AI Automation Developer  
GitHub: **@gaurav-singh-tech**

---

## 📜 License

This project is for personal/professional automation use.  
Feel free to fork, modify, and scale.

---

### 🔥 Built to feel like a real assistant — fast, structured, and intelligent.
