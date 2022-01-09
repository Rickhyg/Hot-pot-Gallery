---
title: Regional variations
layout: index
---

<p> 
    Let's take a look at different kinds of Hot pot in the world!
</p>

{% for variation in site.variations %}

<a href = "/{{variation.title}}"><img src="{{ variation.image-url }}" width = 512></a>
<h4>{{ variation.title }}</h4>
<p>Created by {{ variation.creator }} &nbsp;&nbsp; <a href="{{ variation.licence-url }}">{{ variation.licence }}</a></p>
<p>{{ variation.tag }}</p>

{% endfor %}