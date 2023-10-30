{% include summary.md %}

<ul>
{% for summary in site.summary %}
  <li>
    <a href="{{ summary.url }}">{{ summary.title }}</a>
  </li>
{% endfor %}
</ul>

{% for summary in site.data.sample %}
{{ summary.title }} por {{ summary.author }}
{% endfor %}