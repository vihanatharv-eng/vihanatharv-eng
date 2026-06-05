# Hi, I'm Atharv 👋

Builder. I like shipping things that actually work — usually with a Telegram bot glued to one side.

Currently focused on **AI agents that touch the real world**: scraping, testing, automating, talking to people. Cost-conscious by default; if a free or cheaper model works, I'll use that and tell you.

---

## 🛠️ What I'm shipping

### 🧪 [QA Agent](https://github.com/vihanatharv-eng) — in progress
A Telegram bot that opens any web app, clicks around like a user, watches the console, and reports bugs with evidence. Wraps Playwright + an LLM judgment loop. Built to be the QA hire I can't afford to make yet.

### 🌿 [gracious-greens](https://github.com/vihanatharv-eng/gracious-greens) — live
Planterior brand site. Next.js + NestJS monorepo, Prisma + PostgreSQL, full customer storefront, admin dashboard, and a Telegram bot. The web app is the visible face; the bot is the secret weapon.

### 📹 [AI-summary-for-Hikvision-Cameras](https://github.com/vihanatharv-eng/AI-summary-for-Hikvision-Cameras) — live
Polls a Hikvision NVR, grabs a frame every N minutes, sends it to GPT, emails a daily activity summary. Honest caveat: GPT is asked to *imagine* a summary from the frame, not run real CV. README spells that out.

### 💬 [digital-twin](https://github.com/vihanatharv-eng) — in progress
A WhatsApp digital twin that replies in my tone (Hinglish, short, "Yh" and "Np" included). Started in draft mode — every reply gets approved via Telegram before sending. Slowly graduating to auto-pilot for trusted contacts.

---

## 🧰 Stack I reach for

**Languages:** TypeScript, Python, a little Go when I need it fast
**Frontend:** Next.js, React, Tailwind, vanilla HTML/CSS for throwaway demos
**Backend:** NestJS, FastAPI, Express, Prisma, PostgreSQL, SQLite for local
**Agents / AI:** Playwright, browser-use, OpenRouter (M3 + Sonnet), OpenAI direct, Hermes Agent
**Messaging:** Telegram bots, Green-API for WhatsApp, Python `python-telegram-bot`
**Infra:** WSL on Windows, systemd, cron, GitHub Actions (when forced), Cloudflare when cheap

---

## 💡 How I work

- **Build → ship → iterate** — I'd rather have a working v0 than a perfect v1 in private
- **Cheap first** — default to small models, pay for big ones when the task needs it
- **Sanitize before push** — `.env.example` everywhere, secrets in `.gitignore`, multiple approval gates
- **Document the why** — README, PLAN.md, PROJECT.md per project. Future me is dumb and tired.
- **One-shot research before building** — I always look up competitors, cost, and compatibility before starting something new. Saves weeks.

---

## 📬 Reach me

- **Email:** vihanatharv@gmail.com
- **GitHub:** you're already here
- **Telegram:** ask and I'll share

---

<p align="center">
  <i>"Make it work, make it cheap, then make it fast. In that order."</i>
</p>
