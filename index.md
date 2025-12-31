---
layout: default
title: Welcome to My Blog
---

# Hello, World!

<b>Welcome to my personal blog</b>. This is where I'll share my thoughts, experiences, and insights.

## Recent Posts
{% for post in site.posts limit:3 %}
  - [{{ post.title }}](.{{ post.url }})
{% endfor %}
