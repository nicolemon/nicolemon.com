---
layout: default
title: Nicole A Montano

---

{{ site.data.about.blurb }}

<div id="exit">
<ul>
{% for item in site.data.exitlinks %}
    <li class="{{ item.name }}"><a href="{{ item.url }}"><svg class="{{ item.name }}"></svg></a></li>
{% endfor %}
</ul>
</div>
