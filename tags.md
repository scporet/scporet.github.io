---
layout: default
title: Site Tags
description: Site Categories and Respective Posts
---

<h1>{{ page.title }}</h1>

<p>This page lists all categories tagged to blog posts.  As noted, some blog posts may satisfy more than one category and will be listed here multiple times. </p>

<section>
<div class="card">
{% for tag in site.tags %}
  <span class="b-title">{{ tag[0] | capitalize }}</span>
  <ul>
    {% for post in tag[1] %}
      <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}
</div>

<p><a class="myBtn" href="#top">TOP</a></p>

</section>