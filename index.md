---
layout: default
title: "About"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="About" %}
{% endif %}