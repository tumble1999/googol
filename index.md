---
layout: nul;
---
{% for item in site.pages %}
{% unless item.url == "page.url" %}
[{{ item.title }}]({{ item.url }})
{% endunless %}
{% endfor %}
