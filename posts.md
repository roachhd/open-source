---
layout: default
title: Posts
permalink: /open-source/posts/
---
{% for post in site.posts %}<article><a href="{{ post.url }}"><h2 class="title">{{ post.title }}</h2></a></article>{% endfor %}

