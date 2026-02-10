---
layout: single
permalink: /projects/
title: Projects
author_profile: false
---

Tools I build for my own workflow — mostly CLI tools and native apps. Everything is open source.

{% assign sorted = site.projects | sort: "title" %}
{% for project in sorted %}
- **[{{ project.title }}]({{ project.url | relative_url }})** — {{ project.excerpt | strip_html | strip_newlines }}
{% endfor %}
