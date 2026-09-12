# 🔋 Friendship Battery Percentage

> *“Because apparently friendship needs a battery percentage.”*

A modern, responsive, and humorous web application that pretends to scientifically measure the friendship strength between two people and produces a **Friendship Battery Percentage (0–100%)**, 6 dynamic visual tiers, detailed friendship statistics, a pseudo-AI diagnostic analysis, and an interactive "Friendship Charging" experience.

---

## ✨ Features

- **🔋 Animated Liquid Battery Graphic**: Dynamic SVG fluid fill, bubble physics, and color-coded status tiers (90–100% Best Friends, 75–89% Strong, 50–74% Normal, 25–49% At Risk, 1–24% Critical, 0% Crashed).
- **📝 10 Humorous Multiple-Choice Questions**: Tests food sharing ethics, assignment solidarity, meme transmission frequency, and financial trust.
- **⚡ Fictional Statistics**: Real-time calculated bars for Communication, Food Sharing, Assignment Help, Trust, Meme Sharing, Financial Trust, and Fighting Level.
- **🧠 Pseudo-AI Analysis**: Dynamically generates tailored hilarious roast/praise paragraphs based on both friends' names and actual responses.
- **🔌 Interactive Supercharger Mode**: Simulates 0% → 100% rapid charging with sound, visual overdrive, confetti, and random relationship advice.
- **🎵 Zero-Dependency Web Audio System**: Synthesized futuristic clicks, radar sweeps, charging hums, and celebration fanfares with an easy mute toggle.
- **⚡ Friendship Drainers**: Interactive list of common friendship battery drainers (unanswered texts, borrowed money, eaten fries).
- **📱 Fully Responsive**: Optimized for smartphones, tablets, laptops, and ultra-wide displays.

---

## 🚀 Quick Start (Local)

1. Clone the repository:
   ```bash
   git clone <your-github-repo-url>
   cd friendship
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run dev server:
   ```bash
   npm run dev
   ```
4. Build for production:
   ```bash
   npm run build
   ```

---

## 🌐 Deploying on Render (Free Static Site)

This repository includes a `render.yaml` blueprint for automatic setup, or you can configure it manually in 3 simple steps:

1. Push this project to your GitHub repository (see instructions below).
2. Go to [Render Dashboard](https://dashboard.render.com/) and click **New +** → **Static Site**.
3. Connect your GitHub repository and set:
   - **Name**: `friendship-battery`
   - **Branch**: `main`
   - **Build Command**: `npm run build`
   - **Publish Directory**: `dist`
4. In **Redirects / Rewrites** (under Settings), add:
   - **Source**: `/*`
   - **Destination**: `/index.html`
   - **Action**: `Rewrite`
5. Click **Create Static Site** — Render will build and publish your app with a free HTTPS URL!

---

## ⚠️ Disclaimer

*This friendship score is completely useless and scientifically questionable. Please don't end a friendship because of it.* 😂
