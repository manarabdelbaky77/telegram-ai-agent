# telegram-ai-agent
AI-powered Telegram assistant built with n8n, Google Gemini, Gmail, and Google Sheets for intelligent conversations, email management, and workflow automation.

## 🚀 Features

- 💬 AI-powered conversations through Telegram
- 🤖 Google Gemini AI Agent
- 📧 Read Gmail messages
- 📤 Send emails through Gmail
- 📊 Store messages and responses in Google Sheets
- 🧠 Tool-based AI decision making
- 🔄 Automated workflow orchestration

## 🏗️ Workflow Architecture

```text
Telegram User
      ↓
Telegram Trigger
      ↓
AI Agent
      ↓
Google Gemini
      │
      ├── Gmail → Read Emails
      │
      └── Gmail → Send Emails
      ↓
Telegram Response
      ↓
Google Sheets
