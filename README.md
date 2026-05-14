<div align="center">

# ✦ AI Video Prompt Generator

**Generate cinematic, ready-to-paste prompts for Kling AI & Dreamina — in seconds.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-a78bfa?style=for-the-badge&logo=github)](https://cristinageafar.github.io/ai-video-prompt-generator)
[![Powered by Groq](https://img.shields.io/badge/Powered%20by-Groq%20AI-f472b6?style=for-the-badge)](https://console.groq.com)
[![Model](https://img.shields.io/badge/Model-Llama%203.3%2070B-fb923c?style=for-the-badge)](https://groq.com)
[![Zero Backend](https://img.shields.io/badge/Backend-None%20%E2%80%94%20100%25%20Client%20Side-10b981?style=for-the-badge)]()

<br/>

![App Preview](https://img.shields.io/badge/HTML-Single%20File%20App-06b6d4?style=flat-square)
![No Install](https://img.shields.io/badge/No%20Install-Open%20%26%20Use-7c3aed?style=flat-square)
![Free](https://img.shields.io/badge/Free-Groq%20Free%20Tier-10b981?style=flat-square)

</div>

---

## What it does

Stop spending 30 minutes figuring out what to prompt. This tool takes your niche, platform, and video style — and instantly generates **3 production-ready AI video prompts** optimized specifically for Kling AI or Dreamina.

Each generation gives you:

| Output | Description |
|--------|-------------|
| ⚡ **Hook** | Scroll-stopping first line for your caption |
| 🎬 **3 Video Prompts** | Full text-to-video prompts with camera moves, lighting, style |
| 🚫 **Negative Prompts** | What to exclude for clean results |
| ⚙️ **Settings** | Aspect ratio, duration, motion strength, mode recommendations |
| 🔗 **Combined Edit** | How to merge all 3 clips into one final video |
| ✍️ **Post Caption** | Ready-to-post caption for your chosen platform |
| 🏷️ **Hashtags** | 7 relevant hashtags per generation |

---

## Demo

> Pick your tool → choose your niche & day → hit Generate → paste into Kling / Dreamina

```
Entrepreneur  ×  TikTok  ×  Cinematic  ×  Friday
        ↓
3 cinematic prompts, settings, edit concept, caption + hashtags
```

---

## Supported Tools

### 🎬 Kling AI
- Prompts follow Kling's best-practice format: `subject + action + camera movement + lighting + style`
- Settings include: **5s / 10s** duration, motion strength (low/medium/high), Standard vs Professional mode
- Negative prompts tuned for Kling's model behavior

### ✨ Dreamina (CapCut AI)
- Prompts optimized for Dreamina's style presets: **Realistic, Cinematic, Anime, Illustration**
- Settings include: aspect ratio, **6s** duration, style preset recommendations
- Works with MagicAnimate (image-to-video) workflow too

---

## Getting Started

### 1. Get a Groq API Key (free)

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up for free
3. Navigate to **API Keys** → **Create API Key**
4. Copy your key — it starts with `gsk_`

> Groq's free tier is very generous. The app uses `llama-3.3-70b-versatile` which is fast and free.

### 2. Open the app

**Option A — Live:**
👉 [cristinageafar.github.io/ai-video-prompt-generator](https://crisgea71.github.io/ai-video-prompt-generator/)

**Option B — Local:**
```bash
git clone https://github.com/cristinageafar/ai-video-prompt-generator.git
open ai-video-prompt-generator/index.html
```

### 3. Generate

1. Paste your Groq API key (saved automatically in your browser)
2. Select **Kling AI** or **Dreamina**
3. Pick your post day, niche, platform, and video style
4. Hit **Generate AI Video Prompts**
5. Copy the prompt → paste into your AI video tool → create 🎬

---

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | Vanilla HTML + CSS + JavaScript (zero dependencies) |
| AI | [Groq API](https://console.groq.com) — `llama-3.3-70b-versatile` |
| Hosting | GitHub Pages |
| Storage | `localStorage` (API key only, never leaves your browser) |

**No backend. No database. No tracking. No sign-up.**
Your API key stays in your browser's localStorage and is sent only to Groq's servers.

---

## Creator Niches

| Niche | Prompt Style |
|-------|-------------|
| 💼 Entrepreneur | Office, boardroom, hustle aesthetics, cinematic business |
| 💪 Fitness | Gym, outdoor training, slow-mo, high energy |
| ✨ Lifestyle | Golden hour, aesthetic spaces, fashion, travel |
| 🤖 Tech | Futuristic, screen workflows, neon, editorial |

---

## Why Groq?

[Groq](https://groq.com) runs LLMs on custom hardware (LPUs) that are **10–100x faster** than GPU-based inference. A full generation (3 prompts + settings + caption + hashtags) takes **under 3 seconds**.

| Provider | Speed | Free Tier |
|----------|-------|-----------|
| Groq | ~500 tokens/sec | ✅ Yes |
| OpenAI | ~50 tokens/sec | ❌ Limited |
| Anthropic | ~60 tokens/sec | ❌ No |

---

## Local Development

This is a single HTML file — no build step, no npm, no config.

```bash
git clone https://github.com/cristinageafar/ai-video-prompt-generator.git
cd ai-video-prompt-generator
open index.html   # macOS
# or
start index.html  # Windows
```

To deploy your own version to GitHub Pages:
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your live URL: `https://YOUR_USERNAME.github.io/ai-video-prompt-generator`

---

## License

MIT — use it, fork it, build on it.

---

<div align="center">

Made with ☕ and way too many test prompts.

**[⭐ Star this repo](https://github.com/cristinageafar/ai-video-prompt-generator)** if it saves you time.

</div>
