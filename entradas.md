---
layout: PlantillaSinCarouselsinbarras
title: Lista de Entradas
name: entradas
author: CAPeñarol.CF
date: 2018-04-05 17:45:00 +01:00:00
---

Esta es una lista de entradas de posteos de nuestro sitio:

<br>

{% for post in site.posts %}
<div class="post">
  <h1 class="title"><a href="{{ post.url }}"><span>{{ post.title }}</span></a></h1>
  <p class="byline">Posted on  by <a href="http://xn--capearol-g3a.cf" rel="nofollow">CAPeñarol.CF<img src="{{ site.url }}/images/user.png" width="20px" style="vertical-align:-5px;margin-left:5px;"></a></p>
  <div class="entry">
   <p><img src="{{ post.image1 }}" class="img left" width="250px" style="margin-right:10px;margin-bottom:10px;"><span>{{ post.description }}</span></p>
   <p class="links"><a href="{{ post.url }}" class="more"><button type="button" class="btn btn-mini btn-secondary">leer más</button></a></p>

<br>
<br>
					
  </div>
</div>

<br>
<br>

{% endfor %}

<br>
<br>

<span><a href="xn--capearol-g3a.cf" class="links">CAPeñarol.CF</a></span>
