---
layout: default
title: Home
---

# Welcome to Santosh Blogs 👋
Bookmark this to keep an eye on my project updates!

## Recent Updates

<ul>
  {% for post in site.posts %}
    <li>
      <span style="color: #666; font-family: monospace;">{{ post.date | date: "%b %d, %Y" }}</span> — 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
