---
title: China
layout: index
---

<p> 
    Let's enjoy the types of hot pot in China!
</p>

{% for china in site.china %}

<a href = "/{{china.title}}"><img src="{{ china.image-url }}" width = 512></a>
<h4>{{ china.title }}</h4>
<p>Created by {{ china.creator }} &nbsp;&nbsp; <a href="{{ china.licence-url }}">{{ china.licence }}</a></p>
<p> {{ china.description }} </p>

{% endfor %}
