---
layout: page
title: Somerledi
permalink: /somerledi/
---

{% assign image_files = site.static_files | where: "somerledi_image", true %}
{% for myimage in image_files %}
<img src="{{ site.baseurl }}{{ myimage.path }}">
{% endfor %}
