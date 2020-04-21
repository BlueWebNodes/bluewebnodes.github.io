---
layout: page
title: Jenny's Blog
permalink: /jennysblog/
---

{% for post in site.posts %}

<hr>

# [{{post.title}}]({{site.baseurl}}{{post.url}})

{{post.content|truncatewords:50}})<br />

###### [Read More]({{site.baseurl}}{{post.url}})

{% endfor %}
