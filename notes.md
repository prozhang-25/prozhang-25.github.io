---
layout: default
title: Notes
permalink: /notes/
---

# Notes

## Courses

### International Trade
- 📄 [International Trade Notes (PDF)](/assets/notes/courses/international-trade.pdf)
- 📅 Updated: 2025-01

### Cross-sectional and Panel Data Analysis  
- 📄 [Panel Data Analysis Notes (PDF)](/assets/notes/courses/panel-data-analysis.pdf)
- 📅 Updated: 2025-01

---

## Topics

### CES Utility
- 📄 [CES Utility Function Notes (PDF)](/assets/notes/topics/ces-utility.pdf)
- 📅 Updated: 2025-01

---

## All Notes Posts

{% for post in site.categories.notes %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
