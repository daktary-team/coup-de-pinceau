<h1>Liquid</h1>

{% for page in site.html_pages %}
  {% if page.url != '/' %}
  - [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}

<!--

* virer index de la liste
* virer .html

-->