---
layout: default
title: NT Theology
---

# New Testament Theology

New Testament Theology focuses on the study of the theological themes and teachings presented in the New Testament. It seeks to understand the life, ministry, and teachings of Jesus Christ, as well as the writings of the apostles and early Christian leaders.

## Key Themes

- The Kingdom of God
- Salvation and Grace
- The Role of the Holy Spirit
- The Church and Community
- Eschatology (End Times)

## Explore Posts

Discover more about New Testament Theology through our collection of posts:

{% assign nt_posts = site.posts | where: "categories", "nt-theology" %}
{% for post in nt_posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

Feel free to browse through our articles, sermons, and resources to deepen your understanding of the New Testament and its relevance to your faith journey.