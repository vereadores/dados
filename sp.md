{% include breadcrumbs.html %}

# São Paulo

{% for cidade in site.data.estados.sp %}
- [{{cidade.nome}}](https://vereadores.github.io/dados/sp/)
{% endfor %}
