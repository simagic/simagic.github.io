---
layout: page
title: test
permalink: /hardware/wheels/test/
parent: Custom Wheels
nav_exclude: true
---
# GT Wheels 
{: .no_toc }

1. TOC
{:toc}
<br>


{% for wheel in site.data.ywheels %}
{% if wheel.Style != "GT" and wheel.Style != "GT3" and wheel.Style != "GT4" and wheel.Style != "Formula" and wheel.Style != "Prototype" and wheel.Style != "Standard"%}

## {% if wheel.Brand %}{{ wheel.Brand }} - {% endif %}{% if wheel.Model %}{{ wheel.Model }}<br>{% endif %}
{% if wheel.Brand %}Brand: {{ wheel.Brand }}<br>{% endif %}
{% if wheel.Model %}Model: {{ wheel.Model }}<br>{% endif %}
{% if wheel.Style %}Wheel Style: {{ wheel.Style }}<br>{% endif %}
{% if wheel.Screen %}Screen: {{ wheel.Screen }}<br>{% endif %}
{% if wheel.Width_MM %}Width: {{ wheel.Width_MM }} mm<br>{% endif %}
{% if wheel.LINK %}Link to Product: {{ wheel.LINK }}<br>{% endif %}
{% if wheel.RETAIL_EU %}Price EU: {{ wheel.RETAIL_EU }} EUR<br>{% endif %}
{% if wheel.RETAIL_US %}Price US: {{ wheel.RETAIL_US }} USD<br>{% endif %}
{% if wheel.Comment %}Comments: {{ wheel.Comment }} USD<br>{% endif %}
---
{% endif %}
{% endfor %}
