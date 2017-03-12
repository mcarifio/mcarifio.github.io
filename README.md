---
layout: post
title: Mike@Carif.io's Blog
---



{% for post in site.posts %}

<article class='post'>
  <h1 class='post-title'> {{ post.title }}</h1>
   <p>{{ post.date | date: "%b %-d, %Y" }}</p>
   <p>{{ post.content }}</p>
</article>

{% endfor %}


