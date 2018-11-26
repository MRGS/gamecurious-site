---
layout: default
title: Justice Environnementale & Décolonisation - Environmental Justice & Decolonisation
---

<section id="games" class="container-fluid content-section text-center bg-lightblue" markdown="1">
<br>
## {{ page.title | remove: "Justice Environnementale & Décolonisation - " }} <br> {{ page.title | remove: " - Environmental Justice & Decolonisation" }}
#### 28 Janvier, 2018 — January 28, 2018
<br>
</section>

<div class="text-justify" markdown="1">
{% for game in site.decolonize %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}

{% for game in site.decolonizeextra %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}
</div>
