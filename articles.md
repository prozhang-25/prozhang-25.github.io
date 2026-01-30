---
layout: default
title: Articles
permalink: /articles/
---

# Articles

这里是我的深度文章和研究写作。

---

## 最新文章

{% for post in site.categories.articles limit:10 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

---

## 所有文章

{% for post in site.categories.articles %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
