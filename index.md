---
layout: default
---

# foo!

## posts  

{% for post in site.posts %}
[{{ post.title }}]({{post.url}})
{% endfor %}

## collection sub_pages

{% for pg in site.sub_pages %}
[{{ pg.title }}]({{pg.url}})
{% endfor %}