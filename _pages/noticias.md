---
title: "Notícias"
layout: archive
permalink: /noticias/
author_profile: true
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>