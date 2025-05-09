---
layout: default
title: M. Osawa - Posts
permalink: /posts/
---

<div class="posts-container">
    <h1 class="posts-header">Posts</h1>

    <ul class="posts">
    {% for post in site.posts %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a> <time class="date">{{ post.date | date: "(%B %d, %Y)" }}</time>
        </li>
    {% endfor %}
    </ul>
</div>