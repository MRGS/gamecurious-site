---
layout: default
title: The Games
titre: Les Jeux
---
<section id="games" class="container-fluid content-section text-center bg-yellow" markdown="1">
## {{ page.titre }} <br> {{ page.title }}
</section>

<section id="immigrationgames" class="container-fluid content-section text-center bg-lightyellow" markdown="1">
### Immigration et Frontières <br> Immigration and Borders
#### 21 Janvier, 2018 — January 21, 2018

{% for game in site.immigration %}
<div style="float: {{ game.dir }}"> <img src="/img/immigrationgames/{{ game.img }}" alt="{{ game.title }}"></div>
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>

<section id="decolonizationgames" class="container-fluid content-section text-center bg-lightblue" markdown="1">
### Justice Environnementale & Décolonisation <br> Environmental Justice and Decolonization
#### 28 Janvier, 2018 — January 28, 2018

{% for game in site.decolonize %}
<div style="float: {{ game.dir }}"> <img src="/img/decolonizationgames/{{ game.img }}" alt="{{ game.title }}"></div>
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>

<section id="policinggames" class="container-fluid content-section text-center bg-yellow" markdown="1">
### La Police & Les Prisons <br> Policing & Prisons
#### 4 Février, 2018 — February 4, 2018

{% for game in site.policing %}
<div style="float: {{ game.dir }}"> <img src="/img/policeprisonsgames/{{ game.img }}" alt="{{ game.title }}"></div>
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>


<section id="feminismevent" class="container-fluid content-section text-center bg-lightblue" markdown="1">
### Féminisme & Consentement <br> Feminism & Consent
#### 11 Février, 2018 — February 11, 2018

{% for game in site.feminism %}
<div style="float: {{ game.dir }}"> <img src="/img/feminismevent/{{ game.img }}" alt="{{ game.title }}"></div>
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>
