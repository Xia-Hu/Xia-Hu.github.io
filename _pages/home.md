---
title: "Xia Hu"
layout: homelay
sitemap: false
permalink: /
---

### About Me

<br>

I am currently a software engineer and researcher at Google DeepMind. I live in Los Angeles, California.

Prior to joining Google, I obtained my Ph.D. in Computing Science from [Simon Fraser University](https://www.sfu.ca/)
in 2021, advised by Dr. [Jian Pei](https://sites.google.com/view/jpei/jian-peis-homepage). During my doctoral studies, 
I also 
closely worked and collaborated with Dr. [Oliver Schultte](https://www.cs.sfu.ca/~oschulte/). Before 
pursuing my Ph.D., I worked as a software engineer at Sogou and Baidu. I obtained my B.E. degree in Computer Science 
from the [University of Science and Technology of China](https://www.ustc.edu.cn/) in 2013.


**Research interests:** I am currently working on multimodal LLM, in particular exploring their evolution to 
address application problems. Besides, I am interested in the foundemantal understanding of deep model structures 
from mathematical perspective - previously I focused on model complexity and interpretability.

**Contact me:** amber.hx01@gmail.com

<br/>

### Work Experiences

<div class='jumbotron'>
{% for member in site.data.work %}
<ul>
    <li>
      {{ member.role }} at <b>{{ member.company }}</b> ({{ member.yearStart }} - {{ member.yearEnd }})
    </li>
</ul>
{% endfor %}
</div>

<br/>

### Selected Publications

<div class="jumbotron">
{% bibliography --query @inproceedings %}
</div>

<br/>

### Tutorial 

<div class="jumbotron">
{% bibliography --query @tutorial %}
</div>

<br/>

### Affiliations
<div class="jumbotron">
  <div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
  {% for aff in site.data.affiliation %}<a href="{{ aff.url }}" target="_blank"><img src='{{ site.url }}{{ site.
baseurl }}/images/{{ aff.image }}' style='max-height: 80px; max-width: 150px; margin: 1%'/></a>{% endfor %}
  </div>
</div>
