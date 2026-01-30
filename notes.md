---
layout: default
title: Notes
permalink: /notes/
---

# Notes

这里是我的学习笔记和日常思考记录。

## 分类

- 宏观经济学
- 金融学
- 数学经济学
- 随笔

---

## 最新笔记

{% for post in site.categories.notes limit:10 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

---

## 所有笔记

{% for post in site.categories.notes %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
