---
layout: single
title: Research
permalink: /research/
classes: wide
---

{% for post in site.research %}
### [{{ post.title }}]({{ post.url }})
<p>
   <i>{{ post.venue }}</i><br>
<!-- {{ post.type }} {{ post.date | date: "%Y" }} - {{ post.location }} -->
</p>
{% endfor %}
