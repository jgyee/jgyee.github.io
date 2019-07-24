---
layout: archive
permalink: /projects/
title: "Data Science Projects"
author_profile: true
header:
  overlay_image: "/images/danapointharbor.jpg"
  show_overlay_excerpt: false
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
