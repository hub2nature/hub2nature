---
layout: page
title: "EAA"
permalink: /eaa/
author_profile: true
---

# Extracurricular Artistic Adventures 🎨

<ul>
  {% for post in site.eaa reversed %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
