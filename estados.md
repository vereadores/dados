{% include breadcrumbs.html %}

{% for estado in site.data.estados.estados %}
- <a href="https://vereadores.github.io/dados/{{ estado.sigla }}.html">{{ estado.nome }}</a>
{% endfor %}

