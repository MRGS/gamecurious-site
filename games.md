---
layout: default
title: The Games
titre: Les Jeux
subtitle: Showcase Games
soustitre: Jeux Présentés
---

<section id="games" class="container-fluid content-section text-center bg-yellow" markdown="1">
<br>
## {{ page.titre }} <br> {{ page.title }}

### {{ page.soustitre }} - {{ page.subtitle }}
<br>
</section>

{% assign ev = 'immigrationgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightyellow" markdown="1">

### Immigration & Frontières <br> Immigration & Borders
#### 21 Janvier, 2018 — January 21, 2018

{% for game in site.immigration %}
<div class="text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">
#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }}) 

---

{{ game.content }}

</div>
{% endfor %}

---

<br>

### [Plus de Jeux / More Games]({{ site.baseurl }}{% link immigrationgames.md %})

</section>


{% assign ev = 'decolonizationgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightblue" markdown="1">

### Justice Environnementale & Décolonisation <br> Environmental Justice & Decolonization
#### 28 Janvier, 2018 — January 28, 2018

{% for game in site.decolonize %}
<div class="text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }}) 
{{ game.content }}

</div>
{% endfor %}

---

<br>

### [Plus de Jeux / More Games]({{ site.baseurl }}{% link decolonizegames.md %})

</section>

{% assign ev = 'policeprisonsgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-yellow" markdown="1">

### La Police & Les Prisons <br> Policing & Prisons
#### 4 Février, 2018 — February 4, 2018

{% for game in site.policing %}
<div class="text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

</div>
{% endfor %}

---

<br>

### [Plus de Jeux / More Games]({{ site.baseurl }}{% link policeprisonsgames.md %})

</section>

{% assign ev = 'feminismevent' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightblue" markdown="1">

### Féminisme & Consentement <br> Feminism & Consent
#### 11 Février, 2018 — February 11, 2018

{% for game in site.feminism %}
<div class="text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }}) 
{{ game.content }}

</div>
{% endfor %}

---

<br>

### [Plus de Jeux / More Games]({{ site.baseurl }}{% link feminismevent.md %})

</section>
