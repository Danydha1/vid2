## 🌌 Overview
This project is a fun experiment to explore the feasibility of real-time AI interactions similar to those portrayed in 'gemini-pro vision'.

https://www.youtube.com/watch?v=Bf1zaKUMKeQ

## ✨ Demo

https://danygptvision.vercel.app

You'll need an OpenAI API key. Remember to delete the API key after using it sor safety.

## 🛠 Stack

- Next.js with App Router.
- Vercel AI npm module.
- OpenAI's Whisper and GPT APIs.

## 🚀 Getting Started

You can provide the `OPENAI_API_KEY`` environment variable or let the user provide its own API key in the UI.

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## 🔧 Constants

Some constants are fixed at the top of `/src/app/page.js`. You may want to tweak these :

```js
const INTERVAL = 250;
const IMAGE_WIDTH = 512;
const IMAGE_QUALITY = 0.6;
const COLUMNS = 4;
const MAX_SCREENSHOTS = 60;
const SILENCE_DURATION = 2500;
const SILENT_THRESHOLD = -30;
```
