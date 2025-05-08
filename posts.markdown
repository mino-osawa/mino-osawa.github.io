---
layout: default
title: Thoughts
permalink: /posts/
---

# Posts 
<ul class="posts">
  {% for post in site.posts %}
    <li>
      <time class="date">{{ post.date | date: "%Y-%m-%d" }}</time> – <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
