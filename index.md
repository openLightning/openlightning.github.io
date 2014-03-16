---
title: Home
layout: default
---
<h2> Projects </h2>
<ul>
  <li style="background: #EFD279;">Test</li>
  <li style="background: #95CBE9">Test</li>
  <li class="dark" style="background: #024769; color: #fff;">Test</li>
  <li class="dark" style="background: #2C5700; color: #fff;">Test</li>
  <li style="background: #DE9D7F;">Test</li>
  <li style="background: #EFD279;">Test</li>
  <li style="background: #95CBE9">Test</li>
  <li class="dark" style="background: #024769; color: #fff;">Test</li>
</ul>
{% for post in site.posts %}
{% if forloop.first %}
<h2> Blog </h2>
{% endif %}
<p>&#8618; {{ post.title }} - {{ post.date }}</p>
{% endfor %}
