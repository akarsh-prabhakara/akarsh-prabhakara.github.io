---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% for post in site.projects reversed %}
      {% include single.html %}
{% endfor %}
