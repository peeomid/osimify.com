---
layout: single
title: "recall"
excerpt: "CLI to search and browse AI coding agent conversation history (Claude Code, Codex CLI) locally."
---

## What it is
`recall` is a command-line tool that indexes your AI coding agent conversations into a single local SQLite database. It supports Claude Code, OpenAI Codex CLI, and OpenClaw.

## Why it exists
AI coding tools store your conversation history in different folders and formats. Claude Code uses `.claude/projects`, Codex uses `.codex/sessions`. None of them offer good search across sessions. History gets lost, scattered, and hard to find.

Recall puts everything in one place with full-text search.

## Who it is for
- Developers who use AI coding assistants daily
- Anyone who switches between Claude Code, Codex, or other AI tools
- People who want to search, export, or back up their AI chat history

## Key features
- Full-text search across all AI coding conversations
- Filter by project folder, date range, source tool, or user
- Export sessions to markdown
- JSON output for scripting and automation
- Local-only — no cloud, no data leaves your machine

## Install
```bash
brew install peeomid/tap/recall
```

## Links
- [recall](https://github.com/peeomid/recall)
