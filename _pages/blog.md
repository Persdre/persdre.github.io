---
permalink: /blog/
title: "Thoughts"
layout: default
author_profile: true
---

<span class='anchor' id='thoughts'></span>

# 💭 Thoughts

Here I share some reflections on research, life, and everything in between.

<div class="blog-posts">
{% for post in site.posts %}
  <article class="blog-post">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%Y.%m" }}</p>
    <p>{{ post.excerpt | strip_html | truncate: 200 }}</p>
  </article>
  <hr style="margin: 20px 0;">
{% endfor %}
</div>

{% if site.posts.size == 0 %}
<p>No posts yet. Stay tuned!</p>
{% endif %}
