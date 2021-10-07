---
layout: page
title: Writing
permalink: /writing/
---

<div class="posts">
  {% for post in site.posts %}
    <p class="post_date"></p>
    <p> 
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
        &nbsp;&nbsp;
        {{ post.date | date: "%e/%m/%y" }} 
    </p>
  {% endfor %}
</div>

