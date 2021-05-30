---
layout: page
title: GT Wheels
permalink: /hardware/wheels/gt/
parent: Custom Wheels
---
# GT Wheels 
{: .no_toc }

1. TOC
{:toc}
<br>


{% for wheel in site.data.ywheels %}
{% if wheel.Style == "GT" or wheel.Style == "GT3" or wheel.Style == "GT4" %}

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
