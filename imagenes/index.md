---
layout: PlantillaSinCarouselsinbarras
title: Imágenes del CAPeñarol
name: imagenes
description: Fotos e imágenes del CAPeñarol(R)
tags: fotos imagenes CAPeñarol
author: CAPeñarol
---
<div id="zona-libre">
<h1 style="font-family:fantasy;font-style:italic;color:#000;background:yellow;font-size:1.8em;margin-top:20px;margin-bottom:20px;width:860px;" class="rounded"> Imágenes</h1>

{% for post in site.posts %}
<table class="table table-bordered table-striped table-responsive" style="background:grey;color:#000;font-weight:900;">
  <thead style="color:#fff;font-weight:900;">
    <tr>
      <th style="color:yellow;background:#000;">Imágenes del CAPeñarol<sup>&reg;</sup></th>                            
    </tr>
  </thead>
  <tbody style="background:grey;">
    <tr>
      <td style="background:yellow;"><a href="{{ site.url }}/{{ post.url }}"><h3><span style="color:#000;font-weight:900;font-family:fantasy;">{{ post.title }}</span></h3></a></td>
    </tr>
	<tr>
	  <!--<td><a href="{{ post.image1 }}"><span>{{ post.image1 }}</span></a></td>-->
      <td><a href="{{ post.image1 }}"><span><img src="{{ post.image1 }}" width="800px"></span></a></td>
	</tr>
    {% if post.image2 %}
	  <tr>
	    <!--<td><a href="{{ post.image2 }}"><span>{{ post.image2 }}</span></a></td>-->
        <td><a href="{{ post.image2 }}"><span><img src="{{ post.image2 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
    {% if post.image3 %}
      <tr>
	    <!--<td><a href="{{ post.image3 }}"><span>{{ post.image3 }}</span></a></td>-->
        <td><a href="{{ post.image3 }}"><span><img src="{{ post.image3 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image4 %}
      <tr>
	    <!--<td><a href="{{ post.image4 }}"><span>{{ post.image4 }}</span></a></td>-->
        <td><a href="{{ post.image4 }}"><span><img src="{{ post.image4 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image5 %}
      <tr>
	    <!--<td><a href="{{ post.image5 }}"><span>{{ post.image5 }}</span></a></td>-->
        <td><a href="{{ post.image5 }}"><span><img src="{{ post.image5 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image6 %}
      <tr>
	    <!--<td><a href="{{ post.image6 }}"><span>{{ post.image6 }}</span></a></td>-->
        <td><a href="{{ post.image6 }}"><span><img src="{{ post.image6 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image7 %}
      <tr>
	    <!--<td><a href="{{ post.image7 }}><span>{{ post.image7 }}</span></a></td>-->
        <td><a href="{{ post.image7 }}"><span><img src="{{ post.image7 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image8 %}
      <tr>
	    <!--<td><a href="{{ post.image8 }}><span>{{ post.image8 }}</span></a></td>-->
        <td><a href="{{ post.image8 }}"><span><img src="{{ post.image8 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image9 %}
      <tr>
	    <!--<td><a href="{{ post.image9 }}><span>{{ post.image9 }}</span></a></td>-->
        <td><a href="{{ post.image9 }}"><span><img src="{{ post.image9 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image10 %}
      <tr>
	    <!--<td><a href="{{ post.image10 }}><span>{{ post.image10 }}</span></a></td>-->
        <td><a href="{{ post.image10 }}"><span><img src="{{ post.image10 }}" width="800px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image11 %}
     <tr>
	    <!--<td><a href="{{ post.image11 }}><span>{{ post.image11 }}</span></a></td>-->
        <td><a href="{{ post.image11 }}"><span><img src="{{ post.image11 }}" width="820px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image12 %}
      <tr>
	    <!--<td><a href="{{ post.image12 }}><span>{{ post.image12 }}</span></a></td>-->
        <td><a href="{{ post.image12 }}"><span><img src="{{ post.image12 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image13 %}
      <tr>
	    <!--<td><a href="{{ post.image13 }}><span>{{ post.image13 }}</span></a></td>-->
        <td><a href="{{ post.image13 }}"><span><img src="{{ post.image13 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image14 %}
      <tr>
	    <!--<td><a href="{{ post.image14 }}><span>{{ post.image14 }}</span></a></td>-->
        <td><a href="{{ post.image14 }}"><span><img src="{{ post.image14 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image15 %}
      <tr>
	    <!--<td><a href="{{ post.image15 }}><span>{{ post.image15 }}</span></a></td>-->
        <td><a href="{{ post.image15 }}"><span><img src="{{ post.image15 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image16 %}
      <tr>
	    <!--<td><a href="{{ post.image16 }}><span>{{ post.image16 }}</span></a></td>-->
        <td><a href="{{ post.image16 }}"><span><img src="{{ post.image16 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image17 %}
      <tr>
	    <!--<td><a href="{{ post.image17 }}><span>{{ post.image17 }}</span></a></td>-->
        <td><a href="{{ post.image17 }}"><span><img src="{{ post.image17 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image18 %}
      <tr>
	    <!--<td><a href="{{ post.image18 }}><span>{{ post.image18 }}</span></a></td>-->
        <td><a href="{{ post.image18 }}"><span><img src="{{ post.image18 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image19 %}
      <tr>
	    <!--<td><a href="{{ post.image19 }}><span>{{ post.image19 }}</span></a></td>-->
        <td><a href="{{ post.image19 }}"><span><img src="{{ post.image19 }}" width="820px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image20 %}
      <tr>
	    <!--<td><a href="{{ post.image20 }}><span>{{ post.image20 }}</span></a></td>-->
        <td><a href="{{ post.image20 }}"><span><img src="{{ post.image20 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image21 %}
      <tr>
	    <!--<td><a href="{{ post.image21 }}><span>{{ post.image21 }}</span></a></td>-->
        <td><a href="{{ post.image21 }}"><span><img src="{{ post.image21 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image22 %}
      <tr>
	    <!--<td><a href="{{ post.image22 }}><span>{{ post.image22 }}</span></a></td>-->
        <td><a href="{{ post.image22 }}"><span><img src="{{ post.image22 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image23 %}
      <tr>
	    <!--<td><a href="{{ post.image23 }}><span>{{ post.image23 }}</span></a></td>-->
        <td><a href="{{ post.image23 }}"><span><img src="{{ post.image23 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image24 %}
      <tr>
	    <!--<td><a href="{{ post.image24 }}><span>{{ post.image24 }}</span></a></td>-->
        <td><a href="{{ post.image24 }}"><span><img src="{{ post.image24 }}" width="820px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image25 %}
      <tr>
	    <!--<td><a href="{{ post.image25 }}><span>{{ post.image25 }}</span></a></td>-->
        <td><a href="{{ post.image25 }}"><span><img src="{{ post.image25 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image26 %}
      <tr>
	    <!--<td><a href="{{ post.image26 }}><span>{{ post.image26 }}</span></a></td>-->
        <td><a href="{{ post.image26 }}"><span><img src="{{ post.image26 }}" width="820px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image27 %}
      <tr>
	    <!--<td><a href="{{ post.image27 }}><span>{{ post.image27 }}</span></a></td>-->
        <td><a href="{{ post.image27 }}"><span><img src="{{ post.image27 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image28 %}
      <tr>
	    <!--<td><a href="{{ post.image28 }}><span>{{ post.image28 }}</span></a></td>-->
        <td><a href="{{ post.image28 }}"><span><img src="{{ post.image28 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image29 %}
      <tr>
	    <!--<td><a href="{{ post.image29 }}><span>{{ post.image29 }}</span></a></td>-->
        <td><a href="{{ post.image29 }}"><span><img src="{{ post.image29 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image30 %}
      <tr>
	    <!--<td><a href="{{ post.image30 }}><span>{{ post.image30 }}</span></a></td>-->
        <td><a href="{{ post.image30 }}"><span><img src="{{ post.image30 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image31 %}
      <tr>
	    <!--<td><a href="{{ post.image31 }}><span>{{ post.image31 }}</span></a></td>-->
        <td><a href="{{ post.image31 }}"><span><img src="{{ post.image31 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image32 %}
      <tr>
	    <!--<td><a href="{{ post.image32 }}><span>{{ post.image32 }}</span></a></td>-->
        <td><a href="{{ post.image32 }}"><span><img src="{{ post.image32 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image33 %}
     <tr>
	    <!--<td><a href="{{ post.image33 }}><span>{{ post.image33 }}</span></a></td>-->
        <td><a href="{{ post.image33 }}"><span><img src="{{ post.image33 }}" width="820px"></span></a></td>
	  </tr> 
	{% endif %}
	{% if post.image34 %}
      <tr>
	    <!--<td><a href="{{ post.image34 }}><span>{{ post.image34 }}</span></a></td>-->
        <td><a href="{{ post.image34 }}"><span><img src="{{ post.image34 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image35 %}
      <tr>
	    <!--<td><a href="{{ post.image35 }}><span>{{ post.image35 }}</span></a></td>-->
        <td><a href="{{ post.image35 }}"><span><img src="{{ post.image35 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image36 %}
      <tr>
	    <!--<td><a href="{{ post.image36 }}><span>{{ post.image36}}</span></a></td>-->
        <td><a href="{{ post.image36 }}"><span><img src="{{ post.image36 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image37 %}
      <tr>
	    <!--<td><a href="{{ post.image37 }}><span>{{ post.image37 }}</span></a></td>-->
        <td><a href="{{ post.image37 }}"><span><img src="{{ post.image37 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image38 %}
      <tr>
	    <!--<td><a href="{{ post.image38 }}><span>{{ post.image38 }}</span></a></td>-->
        <td><a href="{{ post.image38 }}"><span><img src="{{ post.image38 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image39 %}
      <tr>
	    <!--<td><a href="{{ post.image39 }}><span>{{ post.image39 }}</span></a></td>-->
        <td><a href="{{ post.image39 }}"><span><img src="{{ post.image39 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image40 %}
      <tr>
	    <!--<td><a href="{{ post.image40 }}><span>{{ post.image40 }}</span></a></td>-->
        <td><a href="{{ post.image40 }}"><span><img src="{{ post.image40 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image41 %}
      <tr>
	    <!--<td><a href="{{ post.image41 }}><span>{{ post.image41 }}</span></a></td>-->
        <td><a href="{{ post.image41 }}"><span><img src="{{ post.image41 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image42 %}
      <tr>
	    <!--<td><a href="{{ post.image42 }}><span>{{ post.image42 }}</span></a></td>-->
        <td><a href="{{ post.image42 }}"><span><img src="{{ post.image42 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image43 %}
      <tr>
	    <!--<td><a href="{{ post.image43 }}><span>{{ post.image43 }}</span></a></td>-->
        <td><a href="{{ post.image43 }}"><span><img src="{{ post.image43 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image44 %}
      <tr>
	    <!--<td><a href="{{ post.image44 }}><span>{{ post.image44 }}</span></a></td>-->
        <td><a href="{{ post.image44 }}"><span><img src="{{ post.image44 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image45 %}
      <tr>
	    <!--<td><a href="{{ post.image45 }}><span>{{ post.image45 }}</span></a></td>-->
        <td><a href="{{ post.image45 }}"><span><img src="{{ post.image45 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image46 %}
        <tr>
	    <!--<td><a href="{{ post.image46 }}><span>{{ post.image46 }}</span></a></td>-->
        <td><a href="{{ post.image46 }}"><span><img src="{{ post.image46 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image47 %}
      <tr>
	    <!--<td><a href="{{ post.image47 }}><span>{{ post.image47 }}</span></a></td>-->
        <td><a href="{{ post.image47 }}"><span><img src="{{ post.image47 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image48 %}
      <tr>
	    <!--<td><a href="{{ post.image48 }}><span>{{ post.image48 }}</span></a></td>-->
        <td><a href="{{ post.image48 }}"><span><img src="{{ post.image48 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	{% if post.image49 %}
      <tr>
	    <!--<td><a href="{{ post.image49 }}><span>{{ post.image49 }}</span></a></td>-->
        <td><a href="{{ post.image49 }}"><span><img src="{{ post.image49 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	<tr>
	{% if post.image50 %}
      <tr>
	    <!--<td><a href="{{ post.image50 }}><span>{{ post.image50 }}</span></a></td>-->
        <td><a href="{{ post.image50 }}"><span><img src="{{ post.image50 }}" width="820px"></span></a></td>
	  </tr>
	{% endif %}
	
  
{% endfor %}
</div>