---
layout: 'layouts/base.njk'
---

{% for post in collections.posts %}
# [{{ post.data.title }}]({{ post.url }})
{{ post.data.description }}
{% endfor %}