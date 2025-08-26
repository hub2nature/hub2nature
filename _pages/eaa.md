---
layout: archive
# title: "EAA"
permalink: /eaa/
author_profile: true
---

# Extracurricular Artistic Adventures 🎨

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-top: 1em;">

  {% for post in site.eaa reversed %}
    <div style="flex: 0 0 20%; text-align: center;">
      <a href="{{ post.url | relative_url }}" style="font-weight: bold; font-size: 1.1em;">
        {{ post.title }}
      </a>
    </div>
  {% endfor %}

</div>
