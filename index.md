# Index
Diese Webseite dient dazu Infomationen für mich,  zu den verschiedenen Software-Entwicklungs Themen, zu sammeln.
## Über mich
Mein Name ist Jean-Marc Wagner und begeisterer mich nun seit mehr als 3 Jahren für den Bereich der Software-Entwicklung. Gerade die Entwicklung mit Python 3 und das Thema der Web-Entwicklung mit allen angegliederten Bereichen (CI, Testing, Interaktionen mit einer Datenbank, Websockets, Docker etc. ) haben es mir echt angetan.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
