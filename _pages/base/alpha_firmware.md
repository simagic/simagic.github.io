---
title: alpha Firmware
layout: page
permalink: /base/alpha_firmware/
parent: Simagic Wheelbase
---
# Firmware Upgrades
The newer versions of Alpha Manager have the updater built into the application.
[Alpha Manager](https://www.simagic.com/#/PageMainEn/PageDownloadEn)

# Firmware Downgrade
In case there is a need to downgrade the Firmware.
The offline updater is available in older versions of the Alpha Manager
Or you can get it from here <a href="/assets/files/alpha/Base_Offline_Updater.zip">Base Offline Updater<a/>

You will also need some old version of the Firmware
{% for firmware in site.assets.files.firmware %}
        <a href="{{ site.baseurl }}{{ firmware.path }}">{{firmware}}<a/>
{% endfor %}
- <a href="/assets/files/alpha/6011.fw">Version 6011<a/>
- <a href="/assets/files/alpha/6016.fw">Version 6016<a/>
- <a href="/assets/files/alpha/6017.fw">Version 6017<a/>
- <a href="/assets/files/alpha/6025.fw">Version 6025<a/>