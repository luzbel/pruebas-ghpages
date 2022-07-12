# pruebas-ghpages
TESTIGO 1
{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
TESTIGO 2

