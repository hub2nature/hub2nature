---
layout: page
title: "EAA"
permalink: /eaa/
author_profile: true
---

# Extracurricular Artistic Adventures 🎨

This section showcases my creative expressions in photography, painting, culinary work, and literature.

---


{% include base_path %}

{% for post in site.eaa reversed %}
  {% include archive-single.html %}
{% endfor %}
