<ul>
{% for estado in site.data.estados %}
  <li>
    <a href="https://vereadores.github.io/dados/{{ estado.sigla }}.html">
      {{ estado.nome }}
    </a>
  </li> 
{% endfor %}
</ul>
