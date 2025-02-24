---
layout: default
title: Medieval Church
---

# Medieval Church History

Medieval Church History delves into the significant events, figures, and developments within the Christian church during the medieval period. This era spans from the fall of the Western Roman Empire to the dawn of the Renaissance, highlighting the church's influence on society, politics, and culture.

## Key Events

- The Rise of the Papacy
- The Great Schism
- The Crusades
- The Inquisition
- The Monastic Reforms

## Explore Posts

Discover more about Medieval Church History through our collection of posts:

{% assign medieval_church_posts = site.posts | where: "categories", "medieval-church" %}
{% for post in medieval_church_posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

Feel free to browse through our articles, sermons, and resources to deepen your understanding of the medieval church and its profound impact on the course of history.