---
layout: default
title: The Games
titre: Les Jeux
---
<section id="games" class="container-fluid content-section text-center bg-yellow" markdown="1">
## {{ page.titre }} <br> {{ page.title }}
</section>

{% assign ev = 'immigrationgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightyellow" markdown="1">
### Immigration et Frontières <br> Immigration and Borders
#### 21 Janvier, 2018 — January 21, 2018

{% for game in site.immigration %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>

{% assign ev = 'decolonizationgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightblue" markdown="1">
### Justice Environnementale & Décolonisation <br> Environmental Justice and Decolonization
#### 28 Janvier, 2018 — January 28, 2018

{% for game in site.decolonize %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>

{% assign ev = 'policeprisonsgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-yellow" markdown="1">
### La Police & Les Prisons <br> Policing & Prisons
#### 4 Février, 2018 — February 4, 2018

{% for game in site.policing %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>

{% assign ev = 'feminismevent' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightblue" markdown="1">
### Féminisme & Consentement <br> Feminism & Consent
#### 11 Février, 2018 — February 11, 2018

{% for game in site.feminism %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">
### {{ game.title }}, [{{ game.web }}](http://{{ game.web }}) <br>{{ game.dev }}

{{ game.content }}

---
<br>

{% endfor %}
</section>
