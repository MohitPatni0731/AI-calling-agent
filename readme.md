# 🩺 Voice AI Appointment Scheduler (Vapi Demo)

A voice receptionist (“Riley”) that books medical appointments. Built with **Vapi.ai** (voice), **OpenAI GPT-4o** (LLM), and **Deepgram Nova-3** (ASR). Includes a live widget demo.

## What it does
- Collects: full name → DOB → phone → reason → preferred date/time.
- Offers fixed demo slots; confirms with code like `WP-12345`.
- Handles reminders (simulated), polite flow, and basic safety language.

## How it’s built
- **Vapi** assistant with a focused system prompt + slot-filling flow.
- **Predefined time slots** → fallback to next business day times.
- **Analysis & success eval** prompts for post-call scoring/summary.
- **Embeddable widget** for instant browser demo.

## Try the demo
GitHub blocks scripts in README. Use the **GitHub Pages** site:
- Live page served from `/docs/index.html` (instructions below).

## Local preview
Open `docs/index.html` in a browser (or use a simple `python -m http.server`).

## Deploy to GitHub Pages
1. Push this repo.
2. In **Settings → Pages**, source: **Deploy from a branch**, folder: `/docs`.
3. Visit the published URL and click **Start** on the widget.

## Config you can edit
- Assistant ID, Public Key
- Theme (dark/light), colors, size, corner radius
- First message, transcript visibility, consent text

---
