---
layout: post
title: Mike@Carif.io's Blog
---



{% for post in site.posts %}

<article class='post'>
  <h1 class='post-title'> {{ post.title }} {{ post.date | date: "%b %-d, %Y" }}</h1>
  {{ post.content }}
</article>

{% endfor %}


