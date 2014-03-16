---
title: Home
layout: default
---
<h2> Home </h2>
<ul>
  <li style="background: #DE9D7F;"><a href="/about.html">About</a></li>
  <li style="background: #EFD279;"><a href="/projects.html">Projects</a></li>
  <li style="background: #95CBE9"><a href="/blog.html">Blog</a></li>
</ul>
{% for post in site.posts %}
{% if forloop.first %}
<h2> Blog </h2>
{% endif %}
<p>&#8618; {{ post.title }} - {{ post.date }}</p>
{% endfor %}
