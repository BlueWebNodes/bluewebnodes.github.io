---
layout: page
title: Blog
permalink: /blog/
---

{% for post in site.posts %}

<hr>

# [{{post.title}}]({{site.baseurl}}{{post.url}})

{{post.content | truncatewords:50}}

###### [Read More]({{site.baseurl}}{{post.url}})

{% endfor %}
