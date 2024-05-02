---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you're interested in joining the group or want to work with us in any way, don't hesitate to reach out.

Our physical address is 
321 Eberhert Building
Greensboro, NC 27403

{%
  include button.html
  type="email"
  text="nicholas.ader@yale.edu"
  link="nicholas.ader@yale.edu"
%}

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

<div class="mapouter"><div class="gmap_canvas"><iframe width="100%" height="100%" id="gmap_canvas" src="https://maps.google.com/maps?q=eberhert%20building&t=&z=15&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe><a href="https://embedgooglemap.net/124/">123movies for free</a><br><style>.mapouter{position:relative;text-align:right;width:100%;height:100%;}</style><a href="https://www.embedgooglemap.net"></a><style>.gmap_canvas {overflow:hidden;background:none!important;width:100%;height:100%;}</style></div></div>

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
