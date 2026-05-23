---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

<p class="blog-subtitle">A retreat against the noise of the world.</p>

<p class="blog-intro">Literature, philosophy, and existentialism through the lens of an engineer.</p>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
