---
layout: default
title: Policing & Prisons
titre: La Police & Les Prisons
---

<section id="games" class="container-fluid content-section text-center bg-yellow" markdown="1">
<br>
## {{ page.titre }} <br> {{ page.title }}
#### 4 Février, 2018 — February 4, 2018
<br>
</section>

<div class="text-justify" markdown="1">
{% for game in site.policing %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}

{% for game in site.policingextra %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}
</div>
