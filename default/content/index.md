---
title: Home
description: Home page
pagination:
  enabled: false
---

# Hello Flatmark!

This is the home page.

---

Dynamic data from `_data/authors.yaml`:

{% for author in site.data.authors %}
- {{ author.name }}, skills: {{ author.skills|join(', ') }}
{% endfor %}