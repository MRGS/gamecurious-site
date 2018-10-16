---
layout: default
title: Games
---
<section id="policinggames" class="class-fluid content-section text-center bg-yellow" markdown="1">
## Policing & Prisons <br> La Police & Les Prisons

{% for game in site.policing %}
<div style="float: {{ game.dir }}"> <img src="/img/policeprisonsgames/{{ game.img }}" alt="{{ game.title }}"></div>
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

<br>

{% endfor %}
</section>
