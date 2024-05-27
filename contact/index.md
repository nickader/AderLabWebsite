---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you're interested in joining our group, or want to work with us in any way, don't hesitate to reach out:

{%
  include button.html
  type="email"
  text="nrader@uncg.edu"
  link="nrader@uncg.edu"
%}

Our physical address is:
<br>
321 Eberhert Building
<br>
321 McIver Street
<br>
Greensboro, NC 27403

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/uncg.jpg"
  caption="University of North Carolina Greensboro"
%}

{% endcapture %}

{% capture col2 %}

<!--From https://www.embedgooglemap.net-->

<div class="mapouter"><div class="gmap_canvas"><iframe width="100%" height="300px" id="gmap_canvas" src="https://maps.google.com/maps?q=eberhert%20building&t=&z=15&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe><a href="https://www.embedgooglemap.net"></a><style>.gmap_canvas {overflow:hidden;background:none!important;width:100%;height:300px;}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
