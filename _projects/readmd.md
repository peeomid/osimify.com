---
layout: single
title: "readmd"
excerpt: "CLI that turns Markdown files into beautiful, portable HTML reading pages."
---

## What it is
`readmd` is a CLI for turning Markdown files into polished HTML pages that feel good to read. It focuses on typography, spacing, colors, code blocks, tables, quotes, and portable output.

![readmd theme and style demo grid](/assets/images/projects/readmd-theme-style-demo.png)

## Why it exists
AI tools create a lot of Markdown: plans, specs, notes, and long reports. Reading those files in a code editor can feel noisy. `readmd` makes a Markdown file easy to turn into a clean reading page with one command.

## Who it is for
- Developers reading AI-generated docs
- People who write notes, specs, or reports in Markdown
- Anyone who wants beautiful HTML output without setting up a site generator

## Key features
- Converts Markdown to a full HTML document
- Writes portable HTML with inline CSS by default
- Supports named color themes and reader styles
- Includes commands to list and print built-in themes and styles
- Supports config from a file, project folder, or user config path

## Quick start
```bash
readmd note.md
```

Choose output:
```bash
readmd note.md --output public/note.html
```

Use a theme and style:
```bash
readmd note.md --theme paper --style notebook
```

## Built with
- Rust

## Links
- [GitHub](https://github.com/peeomid/readmd)
- [Theme and style demos](https://peeomid.github.io/readmd/demos/theme-style/)
