---
layout: page
title: Writing
permalink: /writing/
---

<div class="posts">
  {% for post in site.posts %}
    <p class="post_date"></p>
    <p>
        {{ post.date | date: "%B %e, %Y" }} &nbsp;&nbsp; 
        {{ post.title }}
        (<a href="{{ site.baseurl }}{{ post.url }}">read</a>)
    </p>
  {% endfor %}
</div>

