---
layout: single
permalink: /projects/
title: Projects
author_profile: false
---

Tools I build for my own workflow — mostly CLI tools and native apps. Everything is open source.

<div class="feature__wrapper">
{% assign sorted = site.projects | sort: "title" %}
{% for project in sorted %}
<div class="feature__item">
  <div class="archive__item">
    <div class="archive__item-body">
      <h3 class="archive__item-title"><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
      <div class="archive__item-excerpt">
        <p>{{ project.excerpt | strip_html | strip_newlines }}</p>
      </div>
      <p><a href="{{ project.url | relative_url }}" class="btn btn--primary btn--small">Learn more</a></p>
    </div>
  </div>
</div>
{% endfor %}
</div>
