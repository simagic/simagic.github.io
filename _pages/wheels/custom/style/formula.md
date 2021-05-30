---
layout: page
title: Formula Wheels
permalink: /hardware/wheels/type/formula/
parent: Custom Wheel Styles
grand_parent: Custom Wheels
---
# Formula Wheels 
{: .no_toc }

1. TOC
{:toc}
   
{% for wheel in site.data.ywheels %}
{% if wheel.Style == "Formula" %}

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
