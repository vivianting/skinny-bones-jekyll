
<div class="tiles">
{% for post in site.categories._posts infovis%}
  {% include post-grid.html %}
{% endfor %}
</div>