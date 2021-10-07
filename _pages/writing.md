---
layout: no_title
title: Writing
permalink: /writing/
image: /images/richard-small.jpg
---

<div class="posts">
  {% for post in site.posts %}
    <p class="post_date"></p>
    <p> 
        {{ post.date | date: "%D" }}
        &nbsp;&nbsp;
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> 
    </p>
  {% endfor %}
</div>

