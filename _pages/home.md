---
title: "Darshan Singh S - Home"
layout: gridlay
excerpt: "Darshan Singh S"
sitemap: false
permalink: /
---

<div class="container-fluid">

<div class="row">

<div class="col-sm-8">

Hi! I am a second year MS student in the <a href="https://cvit.iiit.ac.in/">CVIT</a> group at <a href="https://www.iiit.ac.in/">IIIT Hyderabad</a>, advised by <a href="https://faculty.iiit.ac.in/~jawahar/">Prof. C. V. Jawahar</a> and <a href="https://makarandtapaswi.github.io/">Prof. Makarand Tapaswi</a>. I am working in multi-model learning (jointly learning from vision and language modalities). 

Prior to this I was an Engineer at <a href="https://www.mbrdi.co.in/">Mercedes Benz Research & Development India</a>.

I am broadly interested in the problems related to computer vision, natural language processing and multimodal representation learning (especially using self-supervision).

<p align="center">
  <a href="./docs/darshan_resume.pdf">CV</a> /
  <a href="https://scholar.google.com/citations?user=CHFzTuQAAAAJ&hl=en">Google Scholar</a> /
  <a href="https://github.com/Darshansingh11">Github</a> /
  <a href="https://www.linkedin.com/in/darshansinghs">LinkedIn</a> /
</p>

### News
****
{% for article in site.data.news limit:5 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
#### <a href="{{ site.url }}{{ site.baseurl }}/allnews.html">See all news</a>

</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:left; text-align:left">

  <div class="text-left">
  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/photo_darshan.jpeg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->
  <A HREF="mailto:darshan.singh@research.iiit.ac.in">darshan.singh@research.iiit.ac.in</A> <br>

</div>

</div>
</div>

<div class="col-sm-12">

### Publications
****

{% for publi in site.data.publist limit:10 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="250px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">See all publications</a>

</div>


