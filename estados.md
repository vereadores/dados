


{% for estado in site.data.estados %}
- <a href="https://vereadores.github.io/dados/{{ estado.sigla }}.html">{{ estado.nome }}</a>
{% endfor %}

