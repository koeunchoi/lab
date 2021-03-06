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
2020 Fall End of Semester Zoom Lab Party - 12/2/20
(Ava Bir, Koeun Choi, Caroline Kammer, Eman Ayaz, Katie Johnson, Jisun Kim, Breanne De Vera, Anvitha Metpally, Taylor Covington, Michelle Tran, Molly Simek, Martha Drapac, Bethany Grocock, Ally Copeland)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/EndSemLabParty_2020_1202.png" width="70%">
</figure>

2020 Invited Speaker (Sarah Grocock, Montessori Teacher) - October 7
(Bethany Grocock, Koeun Choi, Sarah Grocock)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/LabSpeaker_Grocock_2020_1007.png" width="70%">
</figure>

2020 VT Science Festival - September 29, October 1, October 6 
<a href="https://icat.vt.edu/science-festival/exhibitors/do-you-know-what-i-m-looking-at--tracking-eye-movements-during-m.html">Do you know what I'm looking at? Tracking eye movements during math games </a>
(Koeun Choi, Caroline Hornburg, Ally Copeland, Taylor Covington, Bethany Grocock, Jisun Kim, Ava Bir, Caroline Kammer, Molly Simek, Brianna Whitmore, Breanne De Vera, Shawnice Johnson, Anvitha Metpally, Katie Johnson, Eman Ayaz, Michelle Tran)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/VTSciFest_2020_0929.png" width="70%">
</figure>

2020 Invited Speaker (Wendy Simek, Early Childhood Educator) - September 23
(Jisun Kim, Koeun Choi, Katie Johnson, Taylor Covington, Bethany Grocock, Michelle Tran, Eman Ayaz, Wendy Simek, Ally Copeland, Molly Simek)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/LabSpeaker_Simek_2020_0924.png" width="70%">
</figure>

2020 Lucy Graduation - May 15
(Lucy Shin, Koeun Choi)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/Graduation_Shin_2020_0515.png" width="70%">
</figure>

2020 Spring End of Semester Zoom Lab Party - May 4
(Bethany Grocock, Koeun Choi, Breanne De Vera, Molly Simek, Taylor Covington, Lucy Shin, Michelle Tran, Katie Johnson, Sara Belay, Jisun Kim, Ava Bir, Anvitha Metpally, Rhea Bhatia, Caroline Kammer, Ally Copeland, Jessica Resor, Valerie Salmon, Eva Grumbine, Eman Ayaz)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/EndSemLabParty_2020_0504.png" width="70%">
</figure>

<a href="https://liberalarts.vt.edu/news/academic-news/2020/08/students-participated-in-2020-dennis-dean-conference.html">2020 Dennis Dean Undergraduate Research and Creative Scholarship Conference</a> - April 24
<a href="https://icat.vt.edu/events/2020/05/icat-c-i-day-2020/are-you-still-watching--using-eye-tracking-to-understand-learnin.html">2020 Institute for Creativity, Arts, and Technology (ICAT) Creativity + Innovation Day</a> - May 4
 "Are you still watching on your phone or TV? The impact of mobile media on visual attention and learning" (Sara Belay, Caroline Kammer, Rhea Bhatia, Ally Copeland, Breanne De Vera, Molly Simek, Eva Grumbine, Bethany Grocock, Katie Johnson,  Michelle Tran, Valerie Salmon, Taylor Covington, Anvitha Metpally, Ava Bir, Eman Ayaz)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/URA_2020_0424.png" width="70%">
</figure>

# 2019

2019 Fall End of Semester Lab Pizza Party - December 13
(Lucy Shin, Rhea Bhatia, Ally Copeland, Taylor Covington, Valerie Salmon, Michelle Tran, Jessica Resor, Koeun Choi, Katie Johnson, Ava Bir, Eman Ayaz)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/EndSemLabParty_2019_1213.png" width="70%">
</figure>

2019 VT Science Festival - November 16
(Eman Ayaz, Sara Belay, Rhea Bhatia, Ava Bir, Ally Copeland, Taylor Covington, Breanne De Vera, Eva Grumbine, Bethany Grocock, Katie Johnson, Anvitha Metpally, Michelle Tran, Jessica Resor, Lucy Shin)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/VTSciFest_2019_1116.png" width="70%">
</figure>

2019 Experimental Stimuli Creation - September 13
(Sara Belay, Katie Johnson, Bethany Grocock, Jessica Resor, Sangjin Ko)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/HR_2019_0913.png" width="70%">
</figure>

2019 Dennis Dean Undergraduate Research and Creative Scholarship Conference - April 19
(Ashleigh Bedwell, Katie Johnson, Bethany Grocock, Lucy Shin, Koeun Choi)
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/labpic/URA_2019_0419.png" width="70%">
</figure>
