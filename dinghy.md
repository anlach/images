---
layout: page
title: Dinghy
permalink: /dinghy/
---

{% assign image_files = site.static_files | where: "dinghy_image", true %}
{% for myimage in image_files %}
<img src="{{ site.baseurl }}{{ myimage.path }}">
{% endfor %}
