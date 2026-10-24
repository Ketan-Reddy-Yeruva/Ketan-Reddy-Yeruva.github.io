---
layout: page
title: Blogs
icon: fas fa-pen-nib
order: 2
permalink: /blogs/
---

My thoughts, experiences, and things I learn.

## All Posts

{% assign posts = site.posts %}

{% if posts.size > 0 %}
{% for post in posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt | strip_html | truncatewords: 40 }}

{% endfor %}
{% else %}
No blog posts yet. Check back soon!
{% endif %}
