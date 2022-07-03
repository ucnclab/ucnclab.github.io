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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

------
<!-- 不蒜子访问统计 -->
<p align="right" ><span id="busuanzi_container_site_pv">Page Views:<span id="busuanzi_value_site_pv"></span></p>