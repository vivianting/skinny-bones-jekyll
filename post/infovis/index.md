
<div class="tiles">
{% for post in site.categories.posts infovis_notes%}
  {% include post-grid.html %}
{% endfor %}
</div>