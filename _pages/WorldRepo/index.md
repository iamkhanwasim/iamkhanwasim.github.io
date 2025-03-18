---
title: "Python"
layout: page
permalink: /python/
---
{% for page in site.pages %}
  {% if page.path contains '_pages/Python/' and page.url != '/python/' %}
    - [{{ page.title }}]({{ page.url }})
  {% endif %}
{% endfor %}
