<ul>
{% for estado in site.data.estados %}
  <li>
    <a href="https://vereadores.github.io/dados/{{ estado.Sigla }}.html">
      {{ estado.Nome }}
    </a>
  </li>
{% endfor %}
</ul>
