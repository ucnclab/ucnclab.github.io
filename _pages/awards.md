---
layout: archive
title: "awards"
permalink: /awards/
author_profile: true
---

{% include base_path %}

{% for post in site.awards reversed %}
  {% include archive-single.html %}
{% endfor %}
