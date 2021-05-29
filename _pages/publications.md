---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Papers (coming soon)
======
{% for post in {site.publications| slice:0} reversed %}
  {% include archive-single.html %}
{% endfor %}

Theses
======
{% for post in {site.publications | slice: 1,2} reversed %}
  {% include archive-single.html %}
{% endfor %}
