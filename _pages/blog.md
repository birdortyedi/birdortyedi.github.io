---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

Retreating against the noise of the world..

Thoughts on literature and philosophy (mostly existentialism and absurdism) through the cold, analytical lens of an engineer.

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
