---
layout: post
title:  "Portfolio - Projet de fin de formation"
date:   2017-03-16
excerpt: "Portfolio - Projet de fin de formation - CNAM"
project: true
tag:
- portfolio
- photo
- cnam
- lorraine
comments: false
---

![Moon Homepage]({{ site.url }}/assets/img/travaux/portfolio/Capture1.PNG)    

<center><b>Moon</b> is a minimal, one column jekyll theme.</center>

 Ce portfolio photo est le projet que je devais rendre à la fin de formation au CNAM. Il est responsive et utilise une base de données SQL pour pouvoir créer un compte/se connecter. Le fait de se connecter permet d'accéder à un album en plus. Et il utilise également du PHP pour la partie contact.


## Preview

{% capture images %}
    {{ site.url }}/assets/img/travaux/portfolio/Capture1.PNG"
	{{ site.url }}/assets/img/travaux/portfolio/Capture2.PNG"
	{{ site.url }}/assets/img/travaux/portfolio/Capture3.PNG"
	{{ site.url }}/assets/img/travaux/portfolio/Capture4.PNG"
	{{ site.url }}/assets/img/travaux/portfolio/Capture5.PNG"
{% endcapture %}
{% include gallery images=images caption="Test images" cols=3 %}

<figure class="half">
    <a href="{{ site.url }}/assets/img/travaux/portfolio/Capture1-2.PNG"><img src="{{ site.url }}/assets/img/travaux/portfolio/Capture1.PNG"></a>
	<a href="{{ site.url }}/assets/img/travaux/portfolio/Capture2-2.PNG"><img src="{{ site.url }}/assets/img/travaux/portfolio/Capture2.PNG"></a>
	<a href="{{ site.url }}/assets/img/travaux/portfolio/Capture3-2.PNG"><img src="{{ site.url }}/assets/img/travaux/portfolio/Capture3.PNG"></a>
	<a href="{{ site.url }}/assets/img/travaux/portfolio/Capture4-2.PNG"><img src="{{ site.url }}/assets/img/travaux/portfolio/Capture4.PNG"></a>
	<a href="{{ site.url }}/assets/img/travaux/portfolio/Capture5-2.PNG"><img src="{{ site.url }}/assets/img/travaux/portfolio/Capture5.PNG"></a>
	<figcaption>Caption describing these three images.</figcaption>
</figure>


---
