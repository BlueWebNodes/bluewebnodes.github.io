---
layout: page
title: Jenny's Blog
permalink: /blog/
---

{% for post in site.posts %}

<hr>

# [{{post.title}}]({{site.baseurl}}{{post.url}})

{{post.content|truncatewords:54}}

###### [Read More]({{site.baseurl}}{{post.url}})

{% endfor %}
