# Hi, I'm Yili 👋

I'm a Computer Science student at NTOU. I mainly work with Python and backend systems, and I like building tools that solve problems I actually run into.

## Main project

### [Crypto Flash](https://github.com/Yili-code/Crypto-Flash)

Crypto Flash is the project I use and maintain most often. It monitors crypto news, filters out noise, and sends useful updates to Telegram.

What I have worked on in this project:

- keeping the WebSocket connection alive and reconnecting when it drops
- controlling back-pressure with bounded queues
- handling Telegram rate limits, retries, and message delivery
- storing news for search, daily digests, and event timelines
- running scheduled jobs with GitHub Actions while preserving state
- testing the core logic without production credentials

`Python` `asyncio` `WebSockets` `Telegram Bot API` `GitHub Actions` `pytest`

## Other projects

- [WelfareBridge](https://github.com/Yili-code/WelfareBridge) — A service that matches users with public benefits using official-source crawlers and rule-based eligibility checks.
- [Chronos](https://github.com/Yili-code/Chronos) — A Telegram-first project and task assistant with reminders, repository status, and a small web dashboard.
- [News Agent](https://github.com/Yili-code/News-Agent) — An RSS news collector that removes duplicate stories and sends a daily Telegram briefing.

## Tools I use

- Python, FastAPI, REST APIs
- SQLite, MongoDB, Redis
- Docker, GitHub Actions, Telegram Bot API
- pytest, unittest, Ruff

I care about clear setup instructions, predictable failure handling, and tests that make changes safer. I'm currently preparing for a backend engineering internship and continuing to improve these projects one small, verified change at a time.
