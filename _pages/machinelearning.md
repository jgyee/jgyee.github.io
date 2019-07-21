---
layout: archive
permalink: /projects/
title: "Data Science Projects"
author_profile: true
header:
  image: "/images/danapointharbor.jpg"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
