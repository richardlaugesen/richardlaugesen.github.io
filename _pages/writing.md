---
layout: no_title
title: Writing
permalink: /writing/
image: /images/richard-small.jpg
---

Personal brand? Not much of that going on here. Just whatever I thought may be interesting to others, or my future self, at the time of writing.

<br/>

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
