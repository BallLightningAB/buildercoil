# The Builder Coil

The Builder Coil is the public builder’s log of [Nicolas Brulay/Ball Lightning AB](https://github.com/BallLightningAB), documenting the creation of **Chronomation** — an automation and orchestration engine for modern workflows.

This repo contains:

- The source for the [thebuildercoil.com](https://thebuildercoil.com) site (built with Next.js + MDX)
- Devlogs derived from Chronomation’s changelog
- Experiments with AI, Agentic Development, automation, publishing, and developer storytelling

## 🌀 Purpose

The Builder Coil serves two goals:

1. **Transparency & Community** – Share the journey of building Chronomation.
2. **Product Dogfooding** – Test and showcase Chronomation in a real-world, production setting.

## 📦 Structure

/public → Static assets
/posts → Markdown-based devlogs, auto-generated via Chronomation
/components → Shared React components (e.g. layout, MDX rendering)
/scripts → Utilities and automation hooks
next.config.js → Next.js configuration


## 🔄 Devlog Publishing Flow

This site is powered by **Chronomation**, which:

1. Monitors the Chronomation repo’s changelog (via polling + webhooks)
2. Converts new entries into devlogs
3. Publishes them here to `/posts`
4. (Optionally) Drafts social media updates

> 🏷️ All relevant issues and commits in the private Chronomation repo are tagged with `#thebuildercoil`.

🧠 Tech Stack
Next.js 15 (App Router)
Tailwind CSS
MDX for content
GitHub Actions for CI
Chronomation (private engine powering automation)

🌐 Domains
thebuildercoil.com

© 2025 Nicolas Brulay / Ball Lightning AB
