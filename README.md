# Contributors
{% for member in site.stu %}
  <img src="{{member.image}}">
  <p>{{ member.user }}({{ member.name }})</p>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}
