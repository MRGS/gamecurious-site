---
layout: default
title: Féminisme & Consentement - Feminism & Consent
---

<section id="games" class="container-fluid content-section text-center bg-lightblue" markdown="1">
<br>
## {{ page.title | remove: " - Feminism & Consent" }} <br> {{ page.title | remove: "Féminisme & Consentement - " }}
#### 11 Février, 2018 — February 11, 2018
<br>
</section>

<div class="text-justify" markdown="1">
{% for game in site.feminism %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}

{% for game in site.feminismextra %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}
</div>
