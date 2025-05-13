# Chat-Sprint 🤖 

**Chat-Sprint** is a high-performance, framework-agnostic ChatGPT clone built for rapid prototyping and production-ready AI chat applications. It offers robust chat state management, streaming support, and multi-AI integration capabilities.

---

## 🚀 Features

- **Instant Chat Interface Logic**  
  Out-of-the-box chat infrastructure optimized for real-time interactions, with support for message streaming and efficient updates.

- **Chat State Management**  
  Built-in state management tailored for AI conversations. Handles input, message history, loading states, and streaming tokens with ease.

- **Multi-AI Support**  
  Easily configure and switch between multiple AI models or providers (e.g., OpenAI, Anthropic, Local LLMs) via a unified interface.

- **High Performance**  
  Lightweight and fast. Optimized for low-latency, responsive UIs with minimal overhead.

- **Framework Agnostic**  
  Works with any React-based stack. Compatible with Vercel AI SDK, direct API calls, or custom LLM backends.

---

## File Structure

```
📦 Chat-Sprint
├─ .gitignore
├─ README.md
├─ app
│  ├─ api
│  │  └─ chat
│  │     └─ route.ts
│  ├─ assistant.tsx
│  ├─ favicon.ico
│  ├─ globals.css
│  ├─ layout.tsx
│  └─ page.tsx
├─ components.json
├─ components
│  ├─ app-sidebar.tsx
│  ├─ assistant-ui
│  │  ├─ markdown-text.tsx
│  │  ├─ thread-list.tsx
│  │  ├─ thread.tsx
│  │  └─ tooltip-icon-button.tsx
│  └─ ui
│     ├─ breadcrumb.tsx
│     ├─ button.tsx
│     ├─ input.tsx
│     ├─ separator.tsx
│     ├─ sheet.tsx
│     ├─ sidebar.tsx
│     ├─ skeleton.tsx
│     └─ tooltip.tsx
├─ eslint.config.mjs
├─ hooks
│  └─ use-mobile.ts
├─ lib
│  └─ utils.ts
├─ next.config.ts
├─ package-lock.json
├─ package.json
├─ postcss.config.mjs
└─ tsconfig.json
```

## 🛠️ Installation

```bash
npm install chat-sprint
# or
yarn add chat-sprint

## Getting Started

First, add your AI API key to `.env.local` file and modifying the app/api/route.ts file appropriately: 

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
