---
layout: home
title: Welcome to My Blog
---

# Welcome! 👋

I'm **GuyWithARiceCooker**, and this is my personal blog. Here you'll find my thoughts, ideas, tutorials, and creative projects.

## Latest Posts

{% for post in site.posts limit:3 %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all posts →]({{ site.baseurl }}/blog.html)

---

Feel free to explore and reach out if you have any questions or comments!