---
layout: default
title: Fruits
---

{% for fruits in site.fruits %}

<a href="{{ fruits.url | prepend: site.baseurl }}">
  <h2>{{ fruits.title }}</h2>
</a>

<p class="post-excerpt">{{ fruits.description | truncate: 160 }}</p>

{% endfor %}  
