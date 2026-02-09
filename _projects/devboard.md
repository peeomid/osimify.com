---
layout: single
title: "Devboard"
excerpt: "Native macOS project dashboard — see all your git repos in one app with search, filters, and quick actions."
---

## What it is
Devboard is a lightweight macOS desktop app that shows a visual dashboard of all your local git projects. It reads the data scanned by [`prj`](/projects/prj/) and gives you a searchable, filterable overview with one-click actions to jump into any project.

Think of it as a native companion for your terminal workflow — scan with `prj`, browse with Devboard.

## Why it exists
The original [your-project-dashboard](https://github.com/aviflombaum/your-project-dashboard) by Avi Flombaum is a Rails app — you need to spin up a server every time you want to see your projects. Devboard is a native macOS app that opens instantly. No server, no database, no setup. Just double-click and see everything.

## Who it is for
- Developers who juggle many projects
- Anyone who uses `prj` and wants a visual companion
- People who like native macOS apps over browser tools

## Key features
- Stats bar showing project counts by status
- Quick Resume cards for your most recent active projects
- Full project table sorted by last activity
- Search by name or description with 4 filter dropdowns (status, tech, type, ownership)
- Detail page with tech stack badges, commit timeline, contributors, reference files
- Quick actions: open in Zed, open in Warp, open GitHub, copy path
- Scan Projects button to refresh data
- Dark mode, keyboard shortcuts (Esc, Cmd+F)

## Install
```bash
brew tap peeomid/tap
brew install --cask devboard
```

Requires [`prj`](/projects/prj/) to be installed and scanned first:
```bash
brew install peeomid/tap/prj
prj add ~/Development
prj scan
```

## Built with
- [Tauri v2](https://v2.tauri.app/) (Rust)
- React 19 + TypeScript
- Tailwind CSS 4

## Links
- [GitHub](https://github.com/peeomid/devboard)
- [Download DMG](https://github.com/peeomid/devboard/releases/latest)
- [Homebrew](https://github.com/peeomid/homebrew-tap)
