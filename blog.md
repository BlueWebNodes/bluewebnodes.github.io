---
layout: page
title: Blog
permalink: /blog/
---

{% for post in site.posts %}

[{{ post.title }}]({{ site.baseurl }}{{ post.url }})
============================================================

{{ post.content | truncatewords:54 }}

[Read More]({{ site.baseurl }}{{ post.url }})
