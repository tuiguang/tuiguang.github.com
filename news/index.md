---
layout: splash
title: "热点新闻"
---
{% include JB/setup %}

<ul class="thumbnails">
  {% assign pages_icons = site.categories.itnews %}  
  {% include custom/pages_description %}
</ul>