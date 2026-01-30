---
layout: default
title: Notes
permalink: /notes/
---

# Notes

## Courses

### International Trade
- 📄 [(English) International Trade Notes (PDF)](/assets/notes/courses/international-trade.pdf)
- This is my notes for International Trade (Honor) at Fudan University. The professor of this course is Prof. Luo Changyuan. It covers Ricardian Model for Comparative Advantages, Neoclassical Hecksher-Ohlin Framework, New Trade Theory, and some welfare analysis with respect to tariffs and techonology progress. The model of Eaton and Kortum (2002) and Melitz (2003) is not covered in the notes.

### Cross-sectional and Panel Data Analysis  
- 📄 [Panel Data Analysis Notes (PDF)](/assets/notes/courses/panel-data-analysis.pdf)
- This is my notes for Cross-sectional and Panel Data Analysis at Fudan, which is taught by Prof. Wu Ruochen. It mainly covers LS, GMM, MLE. (Btw, I am not good at Econometrics ...)

### Money and Banking
- 📄 [Money and Banking Notes (PDF)](/assets/notes/courses/money-and-banking.pdf)
- This is my notes for Money and Banking at Fudan, taught by Prof. Sun Lijian. The notes are highly related with Mishkin's textbook, but less related with lectures. Nevertheless, it is a good material for self-learning in order to build a basic framework of monetary economics and to prepare for the final exam.

---

## Topics

### CES Utility
- 📄 [CES Utility Function Notes (PDF)](/assets/notes/topics/ces-utility.pdf)
- CES utility functions and CES production functions are of great importance in fields like international trade and industrial organization. But many teachers assume you have learned this thing somewhere even though it's not the truth. I gathered info and made this notes for self-learning.

---

## All Notes Posts

{% for post in site.categories.notes %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
