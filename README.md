# 🎮 Game Coding Agent

An AI coding agent specialised in game development, powered by **Groq + Llama 3.3 70B**. Completely free — no credit card needed.

![Free](https://img.shields.io/badge/API-free-4ade80?style=flat-square)
![React](https://img.shields.io/badge/React-18-61dafb?style=flat-square&logo=react)
![Vite](https://img.shields.io/badge/Vite-5-646cff?style=flat-square&logo=vite)

## Features

- 🤖 Game dev AI — JS canvas, Phaser 3, Pygame, Unity C#, Godot, and more
- ✨ Streaming responses with live typing
- 🎨 Syntax-highlighted code with copy buttons
- 💬 Full conversation history
- 🚀 Starter prompts to get going instantly
- 💸 **100% free** via Groq's free tier

## Getting Started

### 1. Get a free Groq API key (30 seconds)

1. Go to [console.groq.com](https://console.groq.com)
2. Sign in with Google
3. Click **API Keys** → **Create API Key**
4. Copy the key

### 2. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/game-coding-agent.git
cd game-coding-agent
```

### 3. Install dependencies

```bash
npm install
```

### 4. Add your API key

```bash
cp .env.example .env
```

Open `.env` and paste your key:

```
VITE_GROQ_API_KEY=gsk_...
```

### 5. Run it

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173)

## Deploy for free

Push to GitHub, then import to [Vercel](https://vercel.com):
1. Import your repo
2. Add `VITE_GROQ_API_KEY` in Environment Variables
3. Deploy ✅

## Model

Uses **Llama 3.3 70B** via Groq — Meta's open source model, fast and great at coding.
To switch models, edit the `MODEL` variable in `src/api.js`.
Other free Groq models: `llama-3.1-8b-instant` (faster), `mixtral-8x7b-32768` (long context).

## Tech Stack

- [React 18](https://react.dev) + [Vite 5](https://vitejs.dev)
- [Groq API](https://console.groq.com) (free)
- [Llama 3.3 70B](https://groq.com/llama3) by Meta
- [react-markdown](https://github.com/remarkjs/react-markdown)
- [react-syntax-highlighter](https://github.com/react-syntax-highlighter/react-syntax-highlighter)

## License

MIT
