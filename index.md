---
layout: index
---

<section class="content">
  {% for post in site.posts %}
  <div>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>
	{{ post.content | strip_html | truncatewords: 100 }}
  </p>
  </div>
  {% endfor %}
</section>
