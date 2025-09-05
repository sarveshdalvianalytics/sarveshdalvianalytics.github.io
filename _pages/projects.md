---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
entries_layout: grid
---

{% for project in site.projects reversed %}
  {% include archive-single.html post=project %}
{% endfor %}

