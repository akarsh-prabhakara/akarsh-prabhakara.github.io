---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% assign my_research = "Osprey, 2nd Project, 3rd Project" | split: ", " %}

{% for post in site.projects reversed %}
  {% if my_research contains post.title %}
  	{% include archive-single.html %}
  {% endif %}
{% endfor %}