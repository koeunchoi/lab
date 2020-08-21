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
<a href="https://bit.ly/3aLikHk">School's back, now what? How to navigate education on and offline during the global pandemic</a>
<b> Experts tips for parents newsletter on going back to school by Children and Screens </b>
<b> August 20, 2020 </b>

<a href="https://icat.vt.edu/events/2020/05/icat-c-i-day-2020/are-you-still-watching--using-eye-tracking-to-understand-learnin.html">Are you still watching? Using eye-tracking to understand learning from mobile media</a>
<b> Institute for Creativity, Arts, and Technology (ICAT) Creativity + Innovation Day </b>
<b> May 4, 2020 </b>

# 2019
<a href="https://koeunchoi.github.io/files/Choi_Flyer_2020-0227.pdf">Screen Time for Children</a> 
<b> Rainbow Riders PTA Parent Lecture Series</b>
<b> February 27, 2019 </b>
 
<a href="http://www2.icat.vt.edu/sciencefestival/plan.html">What are you looking at? Eye-tracking technology station</a>
<b> VT Science Festival </b>
<b> November 16, 2019 </b>
