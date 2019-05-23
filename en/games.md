---
layout: default
title: The Games
subtitle: Showcase Games
more: More Games
lang: en
---
<section id="games" class="container-fluid content-section text-center bg-yellow" markdown="1">
<br>
## {{ page.title }}

### {{ page.subtitle }}
<br>
</section>

{% assign ev = 'immigrationgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightyellow" markdown="1">

### {{ site.t.[page.lang].gameslist.immigration.name }}
#### {{ site.t.[page.lang].gameslist.immigration.date }}

{% for game in site.immigration %}
<div class="col-lg-10 col-lg-offset-1 text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">
#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }}) 

---

{{ game.[page.lang] }}

</div>
{% endfor %}

---

<br>

<div class="col-lg-10 col-lg-offset-1 text-center" markdown="1">
### [{{ page.more }}]({{ site.t.[page.lang].gameslist.immigration.url }})
</div>

</section>


{% assign ev = 'decolonizationgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightblue" markdown="1">

### {{ site.t.[page.lang].gameslist.decolonize.name }}
#### {{ site.t.[page.lang].gameslist.decolonize.date }}

{% for game in site.decolonize %}
<div class="col-lg-10 col-lg-offset-1 text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }}) 
{{ game.[page.lang] }}

</div>
{% endfor %}

---

<br>

<div class="col-lg-10 col-lg-offset-1 text-center" markdown="1">
### [{{ page.more }}]({{ site.t.[page.lang].gameslist.decolonize.url }})
</div>

</section>

{% assign ev = 'policeprisonsgames' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-yellow" markdown="1">

### {{ site.t.[page.lang].gameslist.policing.name }}
#### {{ site.t.[page.lang].gameslist.policing.date }}

{% for game in site.policing %}
<div class="col-lg-10 col-lg-offset-1 text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.[page.lang] }}

</div>
{% endfor %}

---

<br>

<div class="col-lg-10 col-lg-offset-1 text-center" markdown="1">
### [{{ page.more }}]({{ site.t.[page.lang].gameslist.policing.url }})
</div>

</section>

{% assign ev = 'feminismevent' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-lightblue" markdown="1">

### {{ site.t.[page.lang].gameslist.feminism.name }}
#### {{ site.t.[page.lang].gameslist.feminism.date }}

{% for game in site.feminism %}
<div class="col-lg-10 col-lg-offset-1 text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }}) 
{{ game.[page.lang] }}

</div>
{% endfor %}

---

<br>

<div class="col-lg-10 col-lg-offset-1 text-center" markdown="1">
### [{{ page.more }}]({{ site.t.[page.lang].gameslist.feminism.url }})
</div>

</section>

{% assign ev = 'capitalism' %}
<section id="{{ ev }}" class="container-fluid content-section text-center bg-yellow" markdown="1">

### {{ site.t.[page.lang].gameslist.capitalism.name }}
#### {{ site.t.[page.lang].gameslist.capitalism.date }}

{% for game in site.capitalism %}
<div class="col-lg-10 col-lg-offset-1 text-justify" markdown="1">
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }}) 
{{ game.[page.lang] }}

</div>
{% endfor %}

---

<br>

<div class="col-lg-10 col-lg-offset-1 text-center" markdown="1">
### [{{ page.more }}]({{ site.t.[page.lang].gameslist.capitalism.url }})
</div>

</section>
