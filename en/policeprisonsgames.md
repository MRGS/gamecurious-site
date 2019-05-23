---
layout: default
lang: en
---
<title>{{ site.t.[page.lang].gameslist.policing.name }}</title>

<section id="games" class="container-fluid content-section text-center bg-yellow" markdown="1">
<br>
## {{ site.t.[page.lang].gameslist.policing.name }}
### {{ site.t.[page.lang].gameslist.policing.date }}
<br>
</section>

<div class="col-lg-10 col-lg-offset-1 text-justify" markdown="1">
{% for game in site.policing %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.[page.lang] }}

{% endfor %}

{% for game in site.policingextra %}
<img src="/img/{{ game.tag }}/{{ game.img }}" alt="{{ game.title }}" class="img-responsive; {{ game.dir }}">

---

#### {{ game.title }}, {{ game.dev }}<br>[{{ game.web }}](http://{{ game.web }})
{{ game.[page.lang] }}

{% endfor %}
</div>
