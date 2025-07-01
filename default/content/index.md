---
title: Home
description: Home page
---

# Hello Flatmark!

This is the home page.

---

Dynamic data from `_data/authors.yaml`:

{% for author in site.data.authors %}
- {{ author.name }}
{% endfor %}
