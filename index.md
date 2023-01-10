---
layout: home
title: Home
nav_exclude: false
nav_order: 0
permalink: /:path/
seo:
  type: Course
  name: AEM 2011 Statics Course
---

# Welcome to Statics

- **Instructor**
  - Hamid Mokhtarzadeh, *(office TBD)*
  - E-mail: mokh0006
  - Office Hours: *TBD*
- **Teaching Assistants and Graders**
  - *(TBD)
- **Lectures:** MWF 9:05-9:55 AM, 105 Tate Hall
- **Textbook:** F.P. Beer, E.R. Johnston, and D.F. Mazurek, Vector Mechanics for Engineers, 12th Edition, McGraw-Hill, 2019
  - *Earlier editions of the book can work for this course.*

----
## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
