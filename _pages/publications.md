---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}


<h2>Conference Papers</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Posters, Demos, Magazines</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'poster' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

