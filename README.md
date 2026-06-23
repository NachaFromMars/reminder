# reminder — Natural-language reminder secretary

> Tell it about a meeting, birthday, or deadline in plain Chinese or English and it schedules Telegram reminders automatically. Events are stored in your workspace and synced across devices.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
reminder is a lightweight personal secretary for OpenClaw. It parses natural-language event descriptions, stores structured event data in your workspace (Git-syncable), and schedules Telegram notifications via OpenClaw cron. Default lead times are 24 hours, 1 hour, and 10 minutes before each event. You can also ask "what's coming up" at any time for a summary of upcoming plans.

## Features
- **Natural-language input** — Chinese and English
- **Structured storage** — events saved to `~/.openclaw/workspace/reminders/events.yml`
- **Telegram reminders** — scheduled via OpenClaw cron (24h / 1h / 10m defaults)
- **Upcoming queries** — "我最近有什么安排" or "what's coming up"
- **Timezone config** — `REMINDER_TZ` env (default `Asia/Shanghai`)
- **Git-syncable** — workspace data syncs across devices via `claw-roam`

## Usage / Quick Start
```
"Meeting with the team Friday at 3pm"
"Mom's birthday on June 30"
"Project deadline next Monday"
"我最近有什么安排？"
```

## Trigger Keywords (OpenClaw)
meeting, birthday, deadline, reminder, schedule, plans, 我最近有什么安排

## Related Skills
- [cron](https://github.com/NachaFromMars) — underlying scheduling engine
- [productivity](https://github.com/NachaFromMars/productivity) — broader time and energy management

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
