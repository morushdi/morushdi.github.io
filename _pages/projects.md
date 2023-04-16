---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
I have worked on several projects during my PhD, MSc, and BSc. Here is a glimpse of some of those projects.
<nbsp>

{% include base_path %}
{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
