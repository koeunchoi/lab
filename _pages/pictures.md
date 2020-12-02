---
title: "Choi Lab - Pictures"
layout: piclay
excerpt: "Choi Lab -- Pictures"
permalink: /pictures/
---

# Pictures

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
2020 End of Semester Zoom Party
(Eman Ayaz, Sara Belay, Rhea Bhatia, Ava Bir, Ally Copeland, Taylor Covington, Breanne De Vera, Eva Grumbine, Bethany Grocock, Katie Johnson, Anvitha Metpally, Michelle Tran, Jessica Resor, Lucy Shin)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/EndSemLabParty_2020_0504.png" width="70%">
</figure>

# 2019
2019 VT Science Festival
(Eman Ayaz, Sara Belay, Rhea Bhatia, Ava Bir, Ally Copeland, Taylor Covington, Breanne De Vera, Eva Grumbine, Bethany Grocock, Katie Johnson, Anvitha Metpally, Michelle Tran, Jessica Resor, Lucy Shin)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/VTSciFest_2019_1116.png" width="70%">
</figure>

2019 Experimental Stimuli Creation
(Sara Belay, Katie Johnson, Bethany Grocock, Jessica Resor, Sangjin Ko)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/HR_2019_0913.png" width="70%">
</figure>

2019 Dennis Dean Undergraduate Research and Creative Scholarship Conference 
(Ashleigh Bedwell, Katie Johnson, Bethany Grocock, Lucy Shin, Koeun Choi)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/URA_2019_0419.png" width="70%">
</figure>
