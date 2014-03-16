---
layout: default
title: Blog
---
{% for post in site.posts %}
{% if forloop.first %}
<h2> Blog </h2>
{% endif %}
<p>&#8618; {{ post.title }} - {{ post.date }}</p>
{% endfor %}
