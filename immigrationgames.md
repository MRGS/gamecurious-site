---
layout: default
title: Immigration & Frontières - Immigration & Borders
titre: 
---

<section id="games" class="container-fluid content-section text-center bg-lightyellow" markdown="1">
<br>
## {{ page.title |  remove: " - Immigration & Borders" }} <br> {{ page.title | remove: "Immigration & Frontières - " }}
#### 21 Janvier, 2018 — January 21, 2018
<br>
</section>

<div class="text-justify" markdown="1">
{% for game in site.immigration %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}

{% for game in site.immigrationextra %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.content }}

{% endfor %}
</div>
