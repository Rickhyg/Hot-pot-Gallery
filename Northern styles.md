---
title: Northern styles
layout: index
---

<p> 
    There are several representative hotpots in Northern China!
</p>

{% for north in site.north %}

<a href = "/{{north.title}}"><img src="{{ north.image-url }}" width = 512></a>
<h4>{{ north.title }}</h4>
<p>Created by {{ north.creator }} &nbsp;&nbsp; <a href="{{ north.licence-url }}">{{ north.licence }}</a></p>

{% endfor %}