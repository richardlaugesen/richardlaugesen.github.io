---
layout: page
title: Writing
permalink: /writing/
---

<div class="posts">
  {% for post in site.posts %}
      <a href="{{ site.baseurl }}{{ post.url }}">
        <p>{{ post.title }}</p>
      </a>
  {% endfor %}
</div>

