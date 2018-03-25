---
layout: PlantillaCarousel
title: Inicio
name: inicio
description: La casa del Club Atlético Peñarol, página de inicio
author: CAPeñarol
---

<br>
<h1 style="font-family:fantasy;font-style:italic;color:#000;background:yellow;" class="rounded"> Inicio</h1>
<br>
<!--<h3 style="font-family:fantasy;font-weight:900;">Calendario - febrero - 2018</h3>
<img src="http://i.imgur.com/FPIKDWs.jpg" width="420px">
<br><br>-->
<span style="font-family:fantasy;font-style:italic;color:yellow;<!--background:#5a5a5a;-->font-size:0.6em;margin-bottom:5px;" class="rounde
d"><center> Último Partido </center></span><br>
<div id="today-update">
  <center>
   <img src="{{ site.url }}/images/955.gif" width="55px" style="display:inline block;"><span style="font-size:2.0em;"> 0 - 2 </span><img src="{{ site.url }}/images/98.gif" width="55px" style="display:inline block;">
  </center>
</div>

<!--<h4><span style="color:#fd5206;text-decoration:underline;font-size:0.5em;">Domingo 11: </span><center><span style="font-family:monospace;font-size:0.7em;color:lightsteelblue;"><img src="{{ site.url }}/images/98.gif" width="30px"> PEÑ 2-1 LIV <img src="{{ site.url }}/images/191.gif" width="30px"></span></center></h4>
<br>-->
<!--<h3 style="font-family:fantasy;font-weight:900;">El Cebolla Rodriguez abrió el tanteador con un taponazo de tiro libre furibundo</h3>
<a href="https://imgur.com/YFRz6z1"><img src="https://i.imgur.com/YFRz6z1.jpg" width="430px" title="source: imgur.com" /></a>
<br>-->
<!--<h3 style="font-family:fantasy;font-weight:900;"><a href="{{ site.url }}/conferencias/conferencia-de-prensa-fecha-no-2-apertura-2018-peñarol-4-1-river-ramos-gargano-giovani">Conferencia de prensa Campeonato Apertura 2018, fecha: No 2, Peñarol 4-1 River</a></h3>-->
<!--<a href="{{ site.url }}/conferencias/conferencia-de-prensa-fecha-no-2-apertura-2018-peñarol-4-1-river-ramos-gargano-giovani"><img src="https://i.imgur.com/LcpKBJ7.jpg" width="130px;" style="margin-right:15px;"><img src="https://i.imgur.com/hFSfsqG.jpg" width="130px;" style="margin-right:15px;"><img src="https://i.imgur.com/Q90UrTe.jpg" width="130px"></a>-->
<br><br>
{% for post in site.posts limit:3 %}
<table class="table table-bordered table-striped table-responsive" style="background:yellow;color:#5a4343;">
  <thead style="color:#fff;font-weight:900;">
    <tr>
    <!-- <th style="font-family:fantasy;font-style:italic;color:#000;background:yellow;"padding:12px;>--><th style="padding:12px;"><h4 style="font-family:fantasy;font-style:italic;color:#000;background:yellow;" class="rounded"><i class="fa fa-globe"></i>Noticias del CAPeñarol<sup>&reg;</sup></h4></th><!--</th>                            -->
    </tr>
  </thead>
  <tbody style="background:#000;">
    <tr>
      <td style="padding:12px;background:#000;"><a href="{{ site.url }}/{{ post.url }}" ><span><h3 style="font-family:fantasy;font-weight:900;">{{ post.title }}</h3></span></a></td>
    </tr>
	<tr>
      <td style="padding:12px;background:stillightblue;"><a href="{{ site.url }}/{{ post.url }}" style="color:#5a4343;"><span>{{ post.description }}</span></a></td>
    </tr>
	<tr>
	  <!--<td style="padding:12px;"><a href="{{ post.image1 }}"><span>{{ post.image1 }}</span></a></td>-->
      <td style="padding:12px;"><a href="{{ post.image1 }}"><span><img src="{{ post.image1 }}" width="393px"></span></a></td>
	</tr>
    {% if post.image2 %}
	  <tr>
	    <!--<td><a href="{{ post.image2 }}"><span>{{ post.image2 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image2 }}"><span><img src="{{ post.image2 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
    {% if post.image3 %}
      <tr>
	    <!--<td><a href="{{ post.image3 }}"><span>{{ post.image3 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image3 }}"><span><img src="{{ post.image3 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image4 %}
      <tr>
	    <!--<td><a href="{{ post.image4 }}"><span>{{ post.image4 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image4 }}"><span><img src="{{ post.image4 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image5 %}
      <tr>
	    <!--<td><a href="{{ post.image5 }}"><span>{{ post.image5 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image5 }}"><span><img src="{{ post.image5 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image6 %}
      <tr>
	    <!--<td><a href="{{ post.image6 }}"><span>{{ post.image6 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image6 }}"><span><img src="{{ post.image6 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image7 %}
      <tr>
	    <!--<td><a href="{{ post.image7 }}><span>{{ post.image7 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image7 }}"><span><img src="{{ post.image7 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image8 %}
      <tr>
	    <!--<td><a href="{{ post.image8 }}><span>{{ post.image8 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image8 }}"><span><img src="{{ post.image8 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image9 %}
      <tr>
	    <!--<td><a href="{{ post.image9 }}><span>{{ post.image9 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image9 }}"><span><img src="{{ post.image9 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image10 %}
      <tr>
	    <!--<td><a href="{{ post.image10 }}><span>{{ post.image10 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image10 }}"><span><img src="{{ post.image10 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image11 %}
     <tr>
	    <!--<td><a href="{{ post.image11 }}><span>{{ post.image11 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image11 }}"><span><img src="{{ post.image11 }}" width="393px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image12 %}
      <tr>
	    <!--<td><a href="{{ post.image12 }}><span>{{ post.image12 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image12 }}"><span><img src="{{ post.image12 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image13 %}
      <tr>
	    <!--<td><a href="{{ post.image13 }}><span>{{ post.image13 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image13 }}"><span><img src="{{ post.image13 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image14 %}
      <tr>
	    <!--<td><a href="{{ post.image14 }}><span>{{ post.image14 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image14 }}"><span><img src="{{ post.image14 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image15 %}
      <tr>
	    <!--<td><a href="{{ post.image15 }}><span>{{ post.image15 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image15 }}"><span><img src="{{ post.image15 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image16 %}
      <tr>
	    <!--<td><a href="{{ post.image16 }}><span>{{ post.image16 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image16 }}"><span><img src="{{ post.image16 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image17 %}
      <tr>
	    <!--<td><a href="{{ post.image17 }}><span>{{ post.image17 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image17 }}"><span><img src="{{ post.image17 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image18 %}
      <tr>
	    <!--<td><a href="{{ post.image18 }}><span>{{ post.image18 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image18 }}"><span><img src="{{ post.image18 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image19 %}
      <tr>
	    <!--<td><a href="{{ post.image19 }}><span>{{ post.image19 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image19 }}"><span><img src="{{ post.image19 }}" width="393px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image20 %}
      <tr>
	    <!--<td><a href="{{ post.image20 }}><span>{{ post.image20 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image20 }}"><span><img src="{{ post.image20 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image21 %}
      <tr>
	    <!--<td><a href="{{ post.image21 }}><span>{{ post.image21 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image21 }}"><span><img src="{{ post.image21 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image22 %}
      <tr>
	    <!--<td><a href="{{ post.image22 }}><span>{{ post.image22 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image22 }}"><span><img src="{{ post.image22 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image23 %}
      <tr>
	    <!--<td><a href="{{ post.image23 }}><span>{{ post.image23 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image23 }}"><span><img src="{{ post.image23 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image24 %}
      <tr>
	    <!--<td><a href="{{ post.image24 }}><span>{{ post.image24 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image24 }}"><span><img src="{{ post.image24 }}" width="393px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image25 %}
      <tr>
	    <!--<td><a href="{{ post.image25 }}><span>{{ post.image25 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image25 }}"><span><img src="{{ post.image25 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image26 %}
      <tr>
	    <!--<td><a href="{{ post.image26 }}><span>{{ post.image26 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image26 }}"><span><img src="{{ post.image26 }}" width="393px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image27 %}
      <tr>
	    <!--<td><a href="{{ post.image27 }}><span>{{ post.image27 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image27 }}"><span><img src="{{ post.image27 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image28 %}
      <tr>
	    <!--<td><a href="{{ post.image28 }}><span>{{ post.image28 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image28 }}"><span><img src="{{ post.image28 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image29 %}
      <tr>
	    <!--<td><a href="{{ post.image29 }}><span>{{ post.image29 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image29 }}"><span><img src="{{ post.image29 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image30 %}
      <tr>
	    <!--<td><a href="{{ post.image30 }}><span>{{ post.image30 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image30 }}"><span><img src="{{ post.image30 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image31 %}
      <tr>
	    <!--<td><a href="{{ post.image31 }}><span>{{ post.image31 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image31 }}"><span><img src="{{ post.image31 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image32 %}
      <tr>
	    <!--<td><a href="{{ post.image32 }}><span>{{ post.image32 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image32 }}"><span><img src="{{ post.image32 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image33 %}
     <tr>
	    <!--<td><a href="{{ post.image33 }}><span>{{ post.image33 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image33 }}"><span><img src="{{ post.image33 }}" width="393px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image34 %}
      <tr>
	    <!--<td><a href="{{ post.image34 }}><span>{{ post.image34 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image34 }}"><span><img src="{{ post.image34 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image35 %}
      <tr>
	    <!--<td><a href="{{ post.image35 }}><span>{{ post.image35 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image35 }}"><span><img src="{{ post.image35 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image36 %}
      <tr>
	    <!--<td><a href="{{ post.image36 }}><span>{{ post.image36}}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image36 }}"><span><img src="{{ post.image36 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image37 %}
      <tr>
	    <!--<td><a href="{{ post.image37 }}><span>{{ post.image37 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image37 }}"><span><img src="{{ post.image37 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image38 %}
      <tr>
	    <!--<td><a href="{{ post.image38 }}><span>{{ post.image38 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image38 }}"><span><img src="{{ post.image38 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image39 %}
      <tr>
	    <!--<td><a href="{{ post.image39 }}><span>{{ post.image39 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image39 }}"><span><img src="{{ post.image39 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image40 %}
      <tr>
	    <!--<td><a href="{{ post.image40 }}><span>{{ post.image40 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image40 }}"><span><img src="{{ post.image40 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image41 %}
      <tr>
	    <!--<td><a href="{{ post.image41 }}><span>{{ post.image41 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image41 }}"><span><img src="{{ post.image41 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image42 %}
      <tr>
	    <!--<td><a href="{{ post.image42 }}><span>{{ post.image42 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image42 }}"><span><img src="{{ post.image42 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image43 %}
      <tr>
	    <!--<td><a href="{{ post.image43 }}><span>{{ post.image43 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image43 }}"><span><img src="{{ post.image43 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image44 %}
      <tr>
	    <!--<td><a href="{{ post.image44 }}><span>{{ post.image44 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image44 }}"><span><img src="{{ post.image44 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image45 %}
      <tr>
	    <!--<td><a href="{{ post.image45 }}><span>{{ post.image45 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image45 }}"><span><img src="{{ post.image45 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image46 %}
        <tr>
	    <!--<td><a href="{{ post.image46 }}><span>{{ post.image46 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image46 }}"><span><img src="{{ post.image46 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image47 %}
      <tr>
	    <!--<td><a href="{{ post.image47 }}><span>{{ post.image47 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image47 }}"><span><img src="{{ post.image47 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image48 %}
      <tr>
	    <!--<td><a href="{{ post.image48 }}><span>{{ post.image48 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image48 }}"><span><img src="{{ post.image48 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image49 %}
      <tr>
	    <!--<td><a href="{{ post.image49 }}><span>{{ post.image49 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image49 }}"><span><img src="{{ post.image49 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
	<tr>
	{% if post.image50 %}
      <tr>
	    <!--<td><a href="{{ post.image50 }}><span>{{ post.image50 }}</span></a></td>-->
        <td style="padding:12px;"><a href="{{ post.image50 }}"><span><img src="{{ post.image50 }}" width="393px"></span></a></td>
	  </tr>
	{% endif %}
  
{% endfor %}
