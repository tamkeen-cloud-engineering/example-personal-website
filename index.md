---
layout: default
title: Home
---

## Hello world

Welcome to my personal webpage.

## My blog posts

Here are my latest blog posts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>
