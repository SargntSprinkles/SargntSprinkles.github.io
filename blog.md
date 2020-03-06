---
layout: page
title: Blog
permalink: /blog/
---
{% for post in site.posts %}
<h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
<p class="author">
<span class="date">{{ post.date }}</span>
</p>
{{ post.excerpt }}
{% endfor %}