---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
I have worked on several projects during my PhD, MSc, and BSc. Here is a glimpse of some of those projects.

{% include base_path %}
{% for post in site.projects %}
  {% include archive-single.html type="grid" %}
{% endfor %}
