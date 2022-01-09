---
title: Southern styles
layout: index
---

<p> 
    There are several representative hotpots in Southern China!
</p>

{% for south in site.south %}

<a href = "/{{south.title}}"><img src="{{ south.image-url }}" width = 512></a>
<h4>{{ south.title }}</h4>
<p>Created by {{ south.creator }} &nbsp;&nbsp; <a href="{{ south.licence-url }}">{{ south.licence }}</a></p>

{% endfor %}