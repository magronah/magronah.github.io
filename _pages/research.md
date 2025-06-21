---
layout: page
title: Research
permalink: /research/
---

## Teaching and Research Experience

{% for post in site.research %}
### [{{ post.title }}]({{ post.url }})
<p>
  {{ post.type }} <i>{{ post.venue }}</i><br>
  {{ post.date | date: "%Y" }} - {{ post.location }}
</p>
{% endfor %}
