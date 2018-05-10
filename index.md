<h1>Liquid</h1>

{% for page in site.html_pages %}
  - [{{ page.title }}]({{ page.url | relative_url }})
{% endfor %}