---
layout: index
---

<section class="content">
  {% for post in site.posts %}
  <div>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>
	{{ post.content | strip_html | truncatewords: 100 }}
  </p>
  </div>
  {% endfor %}
</section>
