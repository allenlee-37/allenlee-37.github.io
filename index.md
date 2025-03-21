---
layout: default
title: Home
---

# 블로그에 오신 걸 환영합니다!

## 최신 포스트

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
