---
layout: archive
title: "Extra-Academic Activities"
permalink: /eaa/
author_profile: true
---

{% include base_path %}

{% for post in site.eaa reversed %}
  {% include archive-single.html %}
{% endfor %}
