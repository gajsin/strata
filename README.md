# 🧠 Strata

**AI-Powered Telegram Mini App — Smart Life Manager**

![React 18](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Database-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-Whisper+GPT-412991?style=flat-square&logo=openai&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

> Full-featured Telegram Mini App with AI assistant, voice control (Whisper), fuzzy search, financial tracking, and habit management — all inside Telegram.

---

## 📸 Screenshots

| | | | | |
|:---:|:---:|:---:|:---:|:---:|
| ![Screen 1](Rectangle.png) | ![Screen 2](Rectangle-1.png) | ![Screen 3](Rectangle-2.png) | ![Screen 4](Rectangle-3.png) | ![Screen 5](Rectangle-4.png) |

---

## ✨ Key Features

### 🎙️ Voice Control (Whisper)
Record voice commands directly in Telegram. Audio is transcribed via OpenAI Whisper and parsed into actionable tasks — "Add meeting tomorrow at 3pm" becomes a calendar entry automatically.

### 🤖 AI Assistant (GPT)
Built-in conversational AI that understands context. Ask it to summarize your day, suggest priorities, or analyze spending patterns across your financial records.

### 🔍 Fuzzy Search
Intelligent search across all entities (tasks, notes, transactions) with typo tolerance. Find "groceries" even if you type "groceris" — powered by custom fuzzy matching algorithm.

### 💰 Financial Tracking
Log income and expenses with categories, tags, and recurring transactions. Visual breakdowns and AI-powered insights help identify spending patterns.

### ✅ Task & Habit Management
Create tasks with priorities, deadlines, and recurrence. Track daily habits with streak counters and completion analytics.

### 📱 Native Telegram Integration
Seamlessly embedded via Telegram SDK. Supports native theme adaptation, haptic feedback, and back button handling for a truly native feel.

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────┐
│              Telegram Mini App (Frontend)         │
│  React 18 · TypeScript · Vite · Tailwind CSS     │
│  Telegram SDK · Voice Recorder · Fuzzy Search    │
├─────────────────────────────────────────────────┤
│                  Backend & Data                   │
│  Supabase (PostgreSQL) · Row Level Security      │
│  Realtime Subscriptions · Auth via Telegram      │
├─────────────────────────────────────────────────┤
│                   AI Layer                        │
│  OpenAI Whisper (Speech-to-Text)                 │
│  GPT-4o (Natural Language Processing)            │
│  Intent Parser · Context Manager                 │
└─────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React 18, TypeScript, Vite |
| **Styling** | Tailwind CSS |
| **Database** | Supabase (PostgreSQL) |
| **AI / NLP** | OpenAI GPT-4o, Whisper |
| **Voice** | MediaRecorder API → Whisper |
| **Search** | Custom fuzzy matching algorithm |
| **Platform** | Telegram Mini Apps SDK |
| **Auth** | Telegram WebApp.initData |

---

## 🔒 Source Code

> **Note:** This repository serves as a portfolio showcase. The full source code is closed/commercial, but the architecture and implementation details can be reviewed upon request during technical interviews.
---

## 📄 License

MIT © 2026 [gajsin](https://github.com/gajsin)
