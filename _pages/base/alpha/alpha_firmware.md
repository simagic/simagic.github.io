---
title: alpha Firmware
layout: page
permalink: /base/alpha_firmware/
grand_parent: Simagic Wheelbase
parent: alpha base
---
# Firmware Upgrades
1. Get [Alpha Manager](https://www.simagic.com/#/PageMainEn/PageDownloadEn)
1. Install / start alpha manager
1. Attach base to computer and boot it
1. Check if base has been found
1. Go to page **BootLoad** and upload the firmware you want (Firmware 2050 is delivered with alpha manager)
1. After firmware is installed, power down the base
1. Wait 10s
1. Power up the base
1. Check if firmware is displayed correctly in alpha manager
1. If the Firmware is 6000 or 0, install again
1. If Firmware is correct, do a factory reset
1. Check [Channel](/base/alpha_channel/)
1. Center your wheel, set your settings and write to base
1. Now you're ready to race



# Firmware Downgrade
In case there is a need to downgrade the Firmware you pretty much follow the same steps as Firmware upgrade.
Do it with the newest alpha manager or you can try the offline updater from here [Base Offline Updater](/assets/files/Base_Offline_Updater.zip)


You will also need some old version of the Firmware

{% for firmware in site.static_files -%}
    {% if firmware.path contains '/assets/files/firmware/alpha/' %}
- <a href="{{ site.baseurl }}{{ firmware.path }}">Version {{firmware.basename}}<a/>
    {%- endif %}
{%- endfor %}
