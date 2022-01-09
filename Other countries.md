---
title: Other Countries
layout: index
---

<p> 
    Come with us to explore the hot pot of other countries except China!
</p>

{% for other in site.others %}
<a href = "/{{other.title}}"><img src="{{ other.image-url }}" width = 512></a>
<h4>{{ other.title }}</h4>
<p>Created by {{ other.creator }} &nbsp;&nbsp; <a href="{{ other.licence-url }}">{{ other.licence }}</a></p>
{% endfor %}