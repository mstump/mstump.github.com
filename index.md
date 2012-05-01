---
layout: page
title: Matt Stump's Blog
tagline: A witty supporting tagline
---

<section class="content">
  <ul class="listing">
    {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
</section>
