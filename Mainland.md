---
title: Mainland
layout: index
---

<p> 
    Hot pot in Chinese mainland is mainly divided into hot pot in the South and North.
</p>

{% for mainland in site.mainland %}

<a href = "/{{mainland.title}}"><img src="{{ mainland.image-url }}" width = 512></a>
<h4>{{ mainland.title }}</h4>
<p>Created by {{ mainland.creator }} &nbsp;&nbsp; <a href="{{ mainland.licence-url }}">{{ mainland.licence }}</a></p>

{% endfor %}