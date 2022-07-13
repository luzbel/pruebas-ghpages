layout: page
title: "PAGE TITLE"
permalink: /URL-PATH/
---
test a
{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
test b
