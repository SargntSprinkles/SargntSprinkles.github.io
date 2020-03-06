---
layout: page
title: Blog
permalink: /blog/
---
{% for post in site.posts %}
<h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
<p>
    <span style="color:gray;font-style:italic;">{{ post.date }}</span>
    {{ post.excerpt }}
</p>
{% endfor %}