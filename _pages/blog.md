---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

<p class="blog-subtitle">Retreating against the noise of the world..</p>

<p class="blog-intro">Thoughts on literature and philosophy (mostly existentialism and absurdism) through the cold, analytical lens of an engineer.</p>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
