---
layout: default
name: Blog Archives
title: Archives
description: Feel free to browse our site history
---


<section class="archive-posts">
<h2>Previous Posts</h2>
    <ul class="myposts">
            {% for post in site.posts offset: 4 %}
    <li class="archive">  
        <a class="b-title" href="{{ post.url }}">{{ post.title}}</a>
        <span class="postDate">({{ post.date | date: "%b %-d, %Y" }})</span>
        <span class="post__desc">{{ post.description }}</span>
    </li>
            {% endfor %}
        </ul>
</section>