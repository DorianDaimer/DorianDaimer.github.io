---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---
{% include base_path %}

<!-- Invited talks (coming soon) -->
{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
