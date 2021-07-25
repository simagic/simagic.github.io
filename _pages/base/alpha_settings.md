---
title: alpha Settings
layout: page
permalink: /base/alpha_settings/
grand_parent: Simagic Wheelbase
parent: alpha base
---
# Settings
For starting here some predefined settings.
However, since setting up for a game is very subjective,
I recommend playing around with the settings yourself and just using these as a bit of a guide.
And just as important, is to set the game settings correct too.
Information on each game can be found [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vRhG6tHBONu3S_K4vcJCQkuDO7XXW7iNyr6FISYhhj5EOyYDTzTvsKjNkDk3lTnYzbg6u2WQgivcgPd/pubhtml?gid=2055729544&single=true)

**Predefined Settings for alpha firmware 6050+**

{% for setting in site.static_files -%}
    {% if setting.path contains '/assets/files/settings/alpha/2050/' %}
- [{{setting.basename}}]({{ site.baseurl }}{{ setting.path }})
    {%- endif %}
{%- endfor %}


**Predefined Settings for older firmware**

{% for setting in site.static_files -%}
    {% if setting.path contains '/assets/files/settings/alpha/older/' %}
- <a href="{{ site.baseurl }}{{ setting.path }}">Version {{setting.basename}}<a/>
    {%- endif %}
{%- endfor %}
