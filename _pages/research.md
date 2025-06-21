---
layout: single
title: Research
permalink: /research/
author_profile: true
classes: wide
---

{% for post in site.research %}
### [{{ post.title }}]({{ post.url }})
<p>
  {{ post.type }}  <i>{{ post.venue }}</i><br>
<!-- {{ post.date | date: "%Y" }} - {{ post.location }} -->
</p>
{% endfor %}
