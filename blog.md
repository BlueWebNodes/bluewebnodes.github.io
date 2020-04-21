---
layout: page
title: Blog
permalink: /blog/
---

<div class="posts" markdown="1">
   {% for post in site.posts %}
    <article class="post" markdown="1">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry" markdown="1">
        {{ post.content | truncatewords:54 }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
