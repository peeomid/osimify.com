---
layout: single
title: "prj"
excerpt: "CLI that scans your local git repos and gives you a project dashboard in the terminal."
---

## What it is
`prj` is a Go CLI that scans your local development folders, reads each git repo, and builds a rich metadata profile — tech stack, recent commits, status, contributors, deployment, TODOs, and more. It stores everything in a single JSON file and lets you browse, search, and filter from the terminal.

## Why it exists
When you have dozens of projects across multiple folders, it's hard to remember what you were working on or what tech each one uses. `prj` gives you that overview as a lightweight CLI — fast enough for AI agents to call directly, and simple enough to pipe into any tool. No server, no database, just a single JSON file on disk.

## Who it is for
- Developers with many local repos
- Anyone who wants a quick way to find and jump into projects
- People who work across multiple languages and frameworks

## Key features
- Scans git repos recursively from any folder
- Detects tech stack, project type, deployment, and status automatically
- Terminal dashboard with stats, filterable list, and detail view
- Outputs structured JSON for tooling and automation
- Pairs with [Devboard](/projects/devboard/) for a visual desktop dashboard

## Install
```bash
brew tap peeomid/tap
brew install prj
```

Or with Go:
```bash
go install github.com/peeomid/prj@latest
```

## Quick start
```bash
prj add ~/Development
prj scan
prj list
prj dash
```

## Links
- [GitHub](https://github.com/peeomid/prj)
- [Homebrew](https://github.com/peeomid/homebrew-tap)
