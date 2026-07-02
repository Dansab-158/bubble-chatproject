# 🫧 Bubble Chat

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
</p>

---

## 📝 Overview
A production-ready social platform with real-time chat, calls, video, screen sharing, and a social feed for sharing short clips. Built with **React 18+**, **TypeScript**, **Redux Toolkit**, **Tailwind CSS + Custom Styled Components**, and **React Router v6**.

## 🚀 Tech Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Framework** | React 18+ | UI framework |
| **Language** | TypeScript | Type safety |
| **Styling** | Tailwind CSS + Custom Styled Components | Utility-first + component-scoped CSS |
| **State** | Redux Toolkit | Global state management |
| **Routing** | React Router v6 | Client-side routing |
| **Icons** | Lucide React | Modern icon library |
| **Forms** | React Hook Form + Zod | Form handling + validation |
| **Mock Data** | MSW (Mock Service Worker) | API mocking |
| **Build** | Vite | Fast bundler |

## ✨ Features
GitHub checkboxes will let you track your progress dynamically:

- [ ] 🔐 **Authentication** — Secure login, registration, and session management.
- [ ] 👥 **Friendship System** — Handle friend requests, status updates, and user lists.
- [ ] 💬 **Text Chat** — Real-time messaging with typing indicators and read receipts.
- [ ] 📱 **Social Feed** — Dedicated space for discovering and sharing short video clips.
- [ ] 📞 **Voice/Video Calls** — High-quality audio and video communication channels.
- [ ] 🖥️ **Screen Sharing** — Instantly share your workspace or screen during active calls.

## 📂 Project Structure

```text
src/
├── app/                    # Redux store configuration
│   ├── store.ts
│   └── hooks.ts            # Typed Redux hooks
├── features/               # Feature-based modules
│   ├── auth/               # Authentication
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   └── types/
│   ├── chat/               # Text chat
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   └── types/
│   ├── friends/            # Friendship system
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   └── types/
│   ├── feed/               # Social feed (posts/clips)
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   └── types/
│   └── calls/              # Voice/Video/Screen share
│       ├── components/
│       ├── pages/
│       ├── store/
│       └── types/
├── components/             # Shared UI components
│   ├── ui/                 # Base components (Button, Modal, etc.)
│   └── layout/             # Layout components (Sidebar, Header, etc.)
├── hooks/                  # Custom reusable hooks
├── utils/                  # Global utility functions
├── types/                  # Global TypeScript types
├── mocks/                  # MSW mock handlers and service configurations
├── pages/                  # Top-level standalone pages (e.g., NotFound)
└── routes/                 # Centralized route definitions
```

## 🛠️ Getting Started
⚠️ Note: Project is currently in active development. Detailed setup instructions will be available soon.

1) Clone the repository
git clone [https://github.com/Dansab-158/bubble-chatproject](https://github.com/Dansab-158/bubble-chatproject)

2) Install dependencies
npm install

3) Run the development server
npm run dev

## 📸 Screenshots & Demo
Coming soon! Check back for visual updates, screenshots, and live demo links.
