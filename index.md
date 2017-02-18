---
layout: nul;
---
{% for item in site.pages %}
{% unless item.url == "page.url" %}
[hi](http://www.com)
{% endunless %}
{% endfor %}
