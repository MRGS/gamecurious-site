---
layout: default
title: Le Capitalisme et Les Luttes Ouvrières - Capitalism and Workers’ Struggles
---

<section id="games" class="container-fluid content-section text-center bg-yellow" markdown="1">
<br>
## {{ page.title | remove: " - Capitalism and Workers’ Struggles" }} <br> {{ page.title | remove: "Le Capitalisme et Les Luttes Ouvrières - " }}
#### 18 Février, 2018 — February 18th, 2018
<br>
</section>

<div class="text-justify" markdown="1">
{% for game in site.capitalism %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}

{% for game in site.capitalismextra %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}
</div>
