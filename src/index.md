---
title: Hello World
layout: "base.njk"
---

Hello Online World!

{% for post in collections.posts %}
- [{{ post.data.title }}]({{ post.url }})
{% endfor %}