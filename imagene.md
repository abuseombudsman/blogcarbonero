---
layout: PlantillaSinCarousel
title: "Contenido: Imagene"
name: imagene
description: Contenido que responde al tema imagene del CAPeñarol(R)
tags: imagene CAPeñarol(R)
author: CAPeñarol
---

<h1 style="font-family:fantasy;font-style:italic;color:#000;background:yellow;font-size:1.8em;margin-top:20px;margin-bottom:20px;" class="rounded"> Contenido: Imagene</h1>
<br>
<br>

<ul>
{% for post in site.categories.imagene %}
	<table class="table table-bordered table-striped table-responsive">
		<header class="post-header">
			<thead style="color:yellow;background:#000;font-weight:900;">
				
					
						<tr width="420px">
							<!--<th id="row">-->
								<!--<th style="color:yellow;background:#000;">-->
									
										<h3><a href="{{ post.url }}"><span itemprop="name headline" style="font-family:fantasy;">{{ post.title | escape }}</span></a></h3>
									
								<!--</th>-->
									
							<!--</th>-->
						</tr>
			</thead>
			<tbody style="color:#000;background:yellow;font-family:fantasy;font-weight:900;">			
   	            
			
				
					<tr>
						<p class="post-meta">
							<td>
								<time id="time">
									<time datetime="{{ page.date | date_to_xmlschema }}"  style="margin-right:10px;">
										{% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
										<i class="glyphicon glyphicon-calendar" style="color:#fd5206;font-size:0.9em;"><span> </span></i>
										<span itemprop="datePublished">{{ post.date | date: date_format }}</span>
									</time>
								</time>
							</td>
							<td>
								<span id="span" itemprop="author" itemscope itemtype="http://schema.org/Person">
									{% if post.author %}
										<i class="glyphicon glyphicon-user" style="color:#fd5206;font-size:0.9em;"><span> </span></i> <span><span itemprop="name" style="margin-right:10px;">{{ post.author }}</span></span>
									{% endif %}
								</span>
							</td>
							<td style="color:#000;background:yellow;">
								<span id="span">
									{% if post.tiempo_de_lectura %}
										<i class="glyphicon glyphicon-time" style="color:#fd5206;font-size:0.9em;"></i><span> </span> <span> lectura:
										{{ post.tiempo_de_lectura }}</span>
									{% endif %}
								</span>
							</td>
						</p>
					</tr>
			</tbody>
        </header>
    </table>


<div class="row-fluid">

  <ul class="thumbnails">
    <li class="span12">
      <div class="thumbnail">
        <center>
	
	      <img data-src="holder.js/300x200" class="image" alt="" src="{{ post.image1 }}" width="420">
	  
	    </center>
        <div class="caption">
		  <p>
	        {{ post.description }}
          </p>
		  {% if fuente %}
			<p>Origen: {{ fuente }}</p><span style="font-size:1,4em;float:right"><i class="fa fa-globe"></i> Noticias</span>
		  {% endif %}
	      <p>
	        <a class="btn btn-lg btn-secondary" href="{{ site.url }}/{{ post.url }}" role="button" style="font-family:fantasy;font-size:0.4;font-style:italic;color:#000;">leer más!</a>
	      </p>
	    </div>
      </div>
    </li>
  </ul>
</div>
{% endfor %}
</ul>