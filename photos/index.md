---
title: Photos
nav:
  order: 4
  tooltip: Photos from the lab!
---

  {% capture content %}
  {% include figure.html image="/images/camera.jpeg" caption="Our new microscope camera arrived! Hello 95% quantum efficency!"%}
  {% include figure.html image="/images/opening.jpg" caption="Ader Lab opened August 1, 2024!"%}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
