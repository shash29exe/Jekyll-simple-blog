---
layout: home
title: Главная
---
## Записи
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%d.%m.%Y" }})
{% endfor %}
