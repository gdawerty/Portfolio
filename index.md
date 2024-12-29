---
layout: home
title: Welcome to my Portfolio
---

![My Logo](docs/assets/AaronLuu.JPG)

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Projects
### Project 1
- Description
- [Github Repository](https://github.com/gdawerty)

- ### Project 2
- Description
- Links

# Education
- Some university and major and possibly GPA

# Work/Experience
- TA
- Research
