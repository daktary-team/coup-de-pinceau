<h1>Liquid</h1>

{% for page in site.pages %}
  - [page.title]({{ page.url }})
{% endfor %}