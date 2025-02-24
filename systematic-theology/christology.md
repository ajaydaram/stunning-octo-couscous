---
layout: default
title: Christology
---

# Christology

Christology is the study of the person and work of Jesus Christ. It explores His identity, His mission, and His significance in the Christian faith.

## Key Themes

- The Incarnation
- The Hypostatic Union
- The Offices of Christ (Prophet, Priest, and King)
- The Atonement
- The Resurrection and Ascension

## Explore Posts

Discover more about Christology through our collection of posts:

{% assign christology_posts = site.posts | where: "categories", "christology" %}
{% for post in christology_posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

Feel free to browse through our articles, sermons, and resources to deepen your understanding of Christology and its significance to your faith journey.