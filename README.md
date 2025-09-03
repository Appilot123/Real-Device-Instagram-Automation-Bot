# Real-Device Instagram Automation Bot

> Control real Android/iOS devices for safe, human-like Instagram growth and operations. Free tier for core actions; Pro adds advanced automations and custom features.

---

## Introduction
A production-grade starter for **real device** Instagram automation. Queue tasks, pace like a human, log everything, and scale from one phone to a farm.

---
<img width="1536" height="500" alt="Image" src="https://github.com/user-attachments/assets/63867c7a-c5a6-4bfc-98a1-336f55950fab" />

---

## Table of content
- [Overview](#overview)
- [Features](#features)
- [Try it for free](#try-it-for-free)
- [Workflow](#workflow)
- [Workflow image](#workflow-image)
- [Key Stats](#key-stats)
- [FAQ](#faq)
- [Contact us](#contact-us)
- [License](#license)
- [Footer image](#footer-image)

---

## Overview
This bot drives **real devices** via ADB/Appium to execute Instagram actions with rate limits, random jitter, and behavior rules. It supports campaign queues, error handling with retries, and structured logs so you can review every action and safely re-run failed steps.

---

## Features

## Features

| # | Feature | Description |
|---|---|---|
| 1 | Follow | Follow targets from lists/queries with smart pacing and random jitter. |
| 2 | Unfollow | Unfollow by lists, FIFO/LIFO, or “non-followers only.” |
| 3 | Share reels | Share any reel to DMs or to your story queue. |
| 4 | Share posts | Share feed posts to DMs or story queue. |
| 5 | Likes | Like posts/reels by hashtag, explore, or lists with daily caps. |
| 6 | Comments | Rotating templates + spintax with per-account cooldowns. |
| 7 | Profile updates | Update bio, name, link, avatar; rotate presets on schedule. |
| 8 | Post reels & images | Upload media from local/URL, caption templates, first-comment. |
| 9 | Story viewing | Warm up accounts by viewing stories with randomized dwell/taps. |
| 10 | Posting story | Post image/video stories, stickers, link stickers (if eligible). |
| 11 | Mass DMs | Personalized DM campaigns with suppression lists and opt-outs. |
| 12 | Auto replies | Rule-based inbox replies by keywords, with cooldown windows. |
| 13 | Mass reporting & blocking | Report/block lists (abuse mitigation/testing workflows). |
| 14 | Scrolling | Human-like scroll/idle/tap patterns to reduce automation traces. |
| 15 | Scheduler | Cron-style start/stop windows per device/campaign. |
| 16 | Device farm manager | Pooling, health checks, failover, per-device fingerprints. |
| 17 | Proxy/SIM rotation | Per-device mobile proxies or SIM data switching (where available). |
| 18 | Analytics & logs | JSON logs, screenshots on error, run summaries and replays. |


> **Free = core actions** (Follow/Unfollow/Share Reels/Share Posts) so people can test stability and pacing. **Pro** unlocks everything else + custom requests.

---

## Try it for free
<img width="1536" height="500" alt="Image" src="https://github.com/user-attachments/assets/388d9d64-266b-45d4-ad91-cb51f2d2c4cf" />

- **Free plan**: Follow, Unfollow, Share Reels, Share Posts  
- **Pro plan**: All features + priority support + custom tasks (contact us)

---

## Workflow

1) **Connect devices** (ADB/Appium) → verify health, proxy/SIM, storage.  
2) **Load campaign** (targets, templates, limits, schedules).  
3) **Humanizer** applies dwell/scroll/jitter rules per action.  
4) **Executor** runs actions with retries + backoff; screenshots on error.  
5) **Logger** writes per-step JSON, aggregates run report.  
6) **Review** results; resume failed steps idempotently.

---

## Workflow image
<img width="1536" height="500" alt="Image" src="https://github.com/user-attachments/assets/7c5dd5bc-d3c2-48bb-a7b1-95804cae4ee8" />

---

## Key Stats
- **Real devices**: Android (USB/Wi-Fi ADB) & iOS (via Appium)  
- **Pacing**: Rate-limit + random jitter; per-action caps  
- **Scale**: Designed for device farms (dozens+) with queues  
- **Reliability**: Retries + exponential backoff + crash recovery  
- **Observability**: JSON logs, screenshots on error, run summaries  
- **Extensible**: Actions are modular; easy to add custom tasks

---

## FAQ

Q: **Is this safe for my accounts?**  
A: No automation is “risk-free.” Use conservative limits, unique device fingerprints, quality proxies/SIMs, and warm accounts first.

Q: **Does the free version include DMs or posting?**  
A: No. Free covers Follow, Unfollow, Share Reels, Share Posts. Pro unlocks DMs, posting, comments, stories, and more.

Q: **Can it run on emulators?**  
A: Primary focus is **real devices**. Emulator support is possible but riskier. We recommend real hardware.

Q: **Does it support multiple accounts/devices?**  
A: Yes. Add devices to the pool; assign campaigns per device with schedules.

Q: **How are limits enforced?**  
A: Global and per-action caps, token-bucket limiter, random jitter, cooldowns, and night-mode windows.

Q: **Can you add a custom feature for me?**  
A: Yes—Pro subscribers can request custom tasks/actions, dashboards, or integrations.

Q: **Compliance & responsibility**  
A: You are responsible for adhering to Instagram’s Terms and applicable laws. Use only with accounts you own/have permission to manage.

---

## Contact us
<p align="center">

  <a href="https://discord.gg/zX7frTbx">
    <img alt="Discord contact" src="https://img.shields.io/badge/Discord-Appilot-5865F2?logo=discord&logoColor=white&style=for-the-badge">
  </a>
  <a href="https://t.me/devpilot1">
    <img alt="Telegram contact" src="https://img.shields.io/badge/Telegram-@devpilot1-2CA5E0?logo=telegram&logoColor=white&style=for-the-badge">
  </a>
</p>

---

## License
MIT — see [LICENSE](./LICENSE)

---

<img width="1536" height="400" alt="Image" src="https://github.com/user-attachments/assets/770f4e0e-934f-4bba-8e18-e295f1f3af21" />
