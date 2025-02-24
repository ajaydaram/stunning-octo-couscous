---
layout: default
title: Theology Proper
---

# Theology Proper

Theology Proper focuses on the study of the nature and attributes of God. It seeks to understand who God is, His character, and His relationship with the world.

## Key Themes

- The Existence of God
- The Attributes of God
- The Trinity
- God's Providence
- The Problem of Evil

## Explore Posts

Discover more about Theology Proper through our collection of posts:

{% assign tp_posts = site.posts | where: "categories", "theology-proper" %}
{% for post in tp_posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

Feel free to browse through our articles, sermons, and resources to deepen your understanding of Theology Proper and its significance to your faith journey.