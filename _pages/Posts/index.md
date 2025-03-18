---
title: "Posts"
layout: page
permalink: /posts/
---
{% for page in site.pages %}
  {% if page.path contains '_pages/Posts/' and page.url != '/posts/' %}
    - [{{ page.title }}]({{ page.url }})
  {% endif %}
{% endfor %}
