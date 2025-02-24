---
layout: default
title: Modern Church
---

# Modern Church History

Modern Church History examines the evolution and transformation of the Christian church from the Reformation period to the present day. It delves into the significant movements, influential figures, and pivotal events that have shaped contemporary Christianity.

## Key Events

- The Reformation
- The Enlightenment and its Impact
- The Great Awakenings
- The Rise of Evangelicalism
- The Ecumenical Movement

## Explore Posts

Discover more about Modern Church History through our collection of posts:

{% assign modern_church_posts = site.posts | where: "categories", "modern-church" %}
{% for post in modern_church_posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

Feel free to browse through our articles, sermons, and resources to deepen your understanding of the modern church and its ongoing influence on global Christianity.