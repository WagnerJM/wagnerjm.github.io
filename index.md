# Index
Diese Webseite dient dazu Infomationen für mich,  zu den verschiedenen Software-Entwicklungs Themen, zu sammeln.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
