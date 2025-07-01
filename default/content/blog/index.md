---
pagination:
  enabled: true
  per_page: 10
  sort_by: -publish_date
---

# My Blog

---
## Manually listed categories

{% for cat in site.categories %}
### {{cat.label}} ({{cat.items|length}})
{% for item in cat.items %}
- [{{item.title}}]({{item.url}})
{% endfor %}

{% endfor %}


---
## Automatically paginated (multiple pages):
