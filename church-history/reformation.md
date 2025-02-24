---
layout: default
title: Reformation
---

# The Reformation

The Reformation was a significant movement in the 16th century that aimed to reform the Roman Catholic Church and led to the establishment of Protestant churches. It was marked by theological debates, political conflicts, and social upheavals.

## Key Figures

- Martin Luther
- John Calvin
- Huldrych Zwingli
- John Knox
- William Tyndale

## Key Events

- The Ninety-Five Theses
- The Diet of Worms
- The Peasants' War
- The Augsburg Confession
- The Council of Trent

## Explore Posts

Discover more about the Reformation through our collection of posts:

{% assign reformation_posts = site.posts | where: "categories", "reformation" %}
{% for post in reformation_posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

Feel free to browse through our articles, sermons, and resources to deepen your understanding of the Reformation and its impact on the development of Christianity.