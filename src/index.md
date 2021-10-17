---
title: Haru Shinogen - A Blog
layout: base.njk
---

![](./images/isshoukenmei-transparent.png)

***NO JS***

## Links

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})

{% endfor %}
