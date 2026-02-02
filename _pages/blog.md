---
permalink: /blog/
title: ""
excerpt: ""
author_profile: true
---

<span class='anchor' id='thoughts'></span>

# 💭 Thoughts

Here I share some reflections on research, life, and everything in between.

## Paul Graham Essays

{% for essay in site.essays %}
{% if essay.path contains 'paul-graham' %}
- [{{ essay.title }}]({{ essay.url }})
{% endif %}
{% endfor %}

## Joel Spolsky Essays

{% for essay in site.essays %}
{% if essay.path contains 'joel-spolsky' %}
- [{{ essay.title }}]({{ essay.url }})
{% endif %}
{% endfor %}

{% if site.essays.size == 0 %}
No essays yet. Stay tuned!
{% endif %}
