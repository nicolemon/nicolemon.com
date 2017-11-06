---
layout: default
title: Nicole A Montano

---

I'm a software engineer in San Jose, California. I like to learn things. Sometimes I do stuff, too.

<div id="exit">
<ul>
{% for item in site.data.exitlinks %}
    <li class="{{ item.name }}"><a href="{{ item.url }}"><svg class="{{ item.name }}"></svg></a></li>
{% endfor %}
</ul>
</div>
