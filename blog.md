---
layout: page
title: UPitch Blog - Presentation Tricks and Tips
header: UPitch Blog
permalink: /blog/
---

<h1></h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>