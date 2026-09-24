---
title: "Social Radar Suite — Open-Source Social Media Management Platform"
description: "Open-source social media management & marketing platform — schedule posts, content calendar, cross-platform analytics dashboards, unified inbox, click-to-WhatsApp bot builder, and an AI assistant. Self-hosted Django + React. A Hootsuite / Buffer / Sprout Social alternative."
---

# Social Radar Suite — Open-Source Social Media Management Platform

**Social Radar Suite** is an open-source, self-hostable **social media management** and
marketing platform for agencies and teams. It's an open alternative to Hootsuite,
Buffer, and Sprout Social, built on **Django + React**.

[⭐ Star the project on GitHub »](https://github.com/swastik-agnihotri/social-radar-suite)

## What it does

- **Social media scheduler & content calendar** — one composer with per-platform
  formatting, brand-voice AI captions, scheduling, and agency approval flows.
- **Social media analytics dashboard** — daily-metric ingestion across Facebook,
  Instagram, YouTube, LinkedIn, and Google Business, with a time-series API and
  per-client dashboards.
- **Unified inbox** — DMs, comments, and Google reviews in one queue, with AI
  reply suggestions in your brand voice.
- **Click-to-WhatsApp bot builder** — a visual flow editor with conditional
  branches and AI chat nodes.
- **Agency marketplace** — a two-sided directory connecting businesses with
  agencies.
- **AI social media assistant** — powered by Anthropic Claude.

## Self-hosting

Social Radar Suite runs on Django 4.2 + Django REST Framework, Celery + Redis, Django
Channels, PostgreSQL, and a React 18 frontend. See the
[installation guide on GitHub](https://github.com/swastik-agnihotri/social-radar-suite#self-hosting--installation-local-dev).

```bash
python manage.py migrate
python manage.py demo_setup   # demo accounts + 90 days of sample analytics
python manage.py runserver
```

## Guides

- [Getting Started](GETTING_STARTED.md)
- [Configuration](CONFIGURATION.md)
- [Connect Social Accounts](CONNECT_ACCOUNTS.md)
- [Connect WhatsApp](CONNECT_WHATSAPP.md)
- [Going Live](GOING_LIVE.md)
- [User Guide](USER_GUIDE.md)
- [FAQ & Troubleshooting](FAQ_TROUBLESHOOTING.md)
- [How it compares](COMPARISON.md)

## Links

- [Source code & README](https://github.com/swastik-agnihotri/social-radar-suite)
- [Contributing guide](https://github.com/swastik-agnihotri/social-radar-suite/blob/main/CONTRIBUTING.md)
- [Report an issue](https://github.com/swastik-agnihotri/social-radar-suite/issues)

---

_Open-source under the MIT License. An open-source alternative to Hootsuite,
Buffer, and Sprout Social._
