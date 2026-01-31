---
permalink: /blog/
title: ""
excerpt: ""
author_profile: true
---

<span class='anchor' id='thoughts'></span>

# 💭 Thoughts

Here I share some reflections on research, life, and everything in between.

{% for post in site.posts %}
- *{{ post.date | date: "%Y.%m" }}*: &nbsp;[{{ post.title }}]({{ post.url }})
{% endfor %}

{% if site.posts.size == 0 %}
No posts yet. Stay tuned!
{% endif %}
