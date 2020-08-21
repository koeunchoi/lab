---
title: "Choi Lab - Outreach"
layout: piclay
excerpt: "Choi Lab -- Outreach"
permalink: /outreach/
---

# Outreach

{% assign number_printed = 0 %}
{% for pic in site.data.pictures %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}


{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

# 2020
<a href="https://bit.ly/3aLikHk">[School's back, now what? How to navigate education on and offline during the global pandemic]
Experts tips for parents newsletter on going back to school by Children and Screens
August 20, 2020

# 2019
2019 VT Science Festival
(Eman Ayaz, Sara Belay, Rhea Bhatia, Ava Bir, Ally Copeland, Taylor Covington, Breanne De Vera, Eva Grumbine, Bethany Grocock, Katie Johnson, Anvitha Metpally, Michelle Tran, Jessica Resor, Lucy Shin)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/VTSciFest_2019_1116.png" width="70%">
</figure>
