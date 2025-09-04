---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
entries_layout: grid
---

{% include base_path %}

{% for project in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
