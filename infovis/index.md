
<div class="tiles">
{% for post in site.categories.post/infovis%}
  {% include post-grid.html %}
{% endfor %}
</div>