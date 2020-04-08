---
layout: layouts/post.njk
title: images
templateClass: tmpl-post
eleventyNavigation:
  key: images
  order: 3
---

{% for image in images reversed %}
[![image {{ image.name }}](/img/images/thumb/{{ image.name }}-sm.jpeg)](/img/images/{{ image.name }}.jpeg)
{% endfor %}


