---
title: "Papers"
layout: page
permalink: /papers/
---
{% for page in site.pages %}
  {% if page.path contains '_pages/Papers/' and page.url != '/papers/' %}
    - [{{ page.title }}]({{ page.url }})
  {% endif %}
{% endfor %}
