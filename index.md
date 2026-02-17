---
layout: default
title: Home
---

<section class="latest-news">
<h1>Latest Science News</h1>
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </li>
{% endfor %}
</ul>
</section>

