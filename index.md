---
layout: page
title: Glossário de Git
---

Um glossário escrito por quem está aprendendo a usar o Git, uma entrada por pessoa.

{% assign entradas = site.pages | where_exp: "p", "p.path contains 'glossario/'" | sort: "title" %}

<ul>
{% for e in entradas %}
  <li><a href="{{ e.url | relative_url }}"><strong>{{ e.title }}</strong></a></li>
{% endfor %}
</ul>

*{{ entradas | size }} entradas até agora.*
