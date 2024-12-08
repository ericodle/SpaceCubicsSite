---
layout: default
title: News
permalink: /ja/news/
---

<h1>News</h1>
<ul>
  {% for post in site.news %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>