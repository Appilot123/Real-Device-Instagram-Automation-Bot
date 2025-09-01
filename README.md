# Real-Device Instagram Automation Bot

> Control real Android/iOS devices for safe, human-like Instagram growth and operations. Free tier for core actions; Pro adds advanced automations and custom features.

---

## Repository name
**Real-Device-Instagram-Automation-Bot**

---

## Introduction
A production-grade starter for **real device** Instagram automation. Queue tasks, pace like a human, log everything, and scale from one phone to a farm.

---

## Hero image
![Hero](./assets/hero.png)

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
![Try it free](./assets/try-free.png)

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
![Workflow](./assets/workflow.png)

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

**Is this safe for my accounts?**  
No automation is “risk-free.” Use conservative limits, unique device fingerprints, quality proxies/SIMs, and warm accounts first.

**Does the free version include DMs or posting?**  
No. Free covers Follow, Unfollow, Share Reels, Share Posts. Pro unlocks DMs, posting, comments, stories, and more.

**Can it run on emulators?**  
Primary focus is **real devices**. Emulator support is possible but riskier. We recommend real hardware.

**Does it support multiple accounts/devices?**  
Yes. Add devices to the pool; assign campaigns per device with schedules.

**How are limits enforced?**  
Global and per-action caps, token-bucket limiter, random jitter, cooldowns, and night-mode windows.

**Can you add a custom feature for me?**  
Yes—Pro subscribers can request custom tasks/actions, dashboards, or integrations.

**Compliance & responsibility**  
You are responsible for adhering to Instagram’s Terms and applicable laws. Use only with accounts you own/have permission to manage.

---

## Contact us
- Telegram: **@devpilot1**  
- Discord: **Appilot** (server)  
- GitHub: **Appilot123**  
- Website: **bitbash.dev**

---

## License
MIT — see [LICENSE](./LICENSE)

---

## Footer image
![Footer](./assets/footer.png)
