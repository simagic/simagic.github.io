---
title: alpha Firmware
layout: page
permalink: /base/alpha_firmware/
grand_parent: Simagic Wheelbase
parent: alpha base
---
# Firmware Upgrades
The newer versions of Alpha Manager have the updater built into the application.
[Alpha Manager](https://www.simagic.com/#/PageMainEn/PageDownloadEn)

# Firmware Downgrade
In case there is a need to downgrade the Firmware.
The offline updater is available in older versions of the Alpha Manager
Or you can get it from here <a href="/assets/files/alpha/Base_Offline_Updater.zip">Base Offline Updater<a/>

You will also need some old version of the Firmware

{% for firmware in site.static_files -%}
    {% if firmware.path contains '/assets/files/firmware/alpha/' %}
- <a href="{{ site.baseurl }}{{ firmware.path }}">Version {{firmware.basename}}<a/>
    {%- endif %}
{%- endfor %}
