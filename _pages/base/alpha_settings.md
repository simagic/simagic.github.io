---
title: alpha Settings
layout: page
permalink: /base/alpha_settings/
grand_parent: Simagic Wheelbase
parent: alpha base
---
# Settings
For starting here some predefined settings.
However since setting up for a game is very subjective,
I recomend playing around with the settings yourself and just using these as a bit of a guide.

**Predefined Settings for alpha firmware 6050+**

{% for setting in site.static_files -%}
    {% if setting.path contains '/assets/files/settings/alpha/2050/' %}
- <a href="{{ site.baseurl }}{{ setting.path }}">Version {{setting.basename}}<a/>
    {%- endif %}
{%- endfor %}


**Predefined Settings for older firmware**

{% for setting in site.static_files -%}
    {% if setting.path contains '/assets/files/settings/alpha/older/' %}
- <a href="{{ site.baseurl }}{{ setting.path }}">Version {{setting.basename}}<a/>
    {%- endif %}
{%- endfor %}
