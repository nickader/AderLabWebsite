---
title: Photos
nav:
  order: 4
  tooltip: Photos from the lab!
---

  {% capture content %}
  {% include figure.html image="/images/photos/241119_hike2.jpeg" caption="Charlotte giving Julep some good pets"%}
  {% include figure.html image="/images/photos/241119_hike1.jpeg" caption="Eric (Adamson lab), Charlotte, Nick (& Julep!), and Sara"%}
  {% include figure.html image="/images/halloween24.jpeg" caption="Halloween 2024!"%}
  {% include figure.html image="/images/camera.jpeg" caption="Our new microscope camera arrived! Hello 95% quantum efficency!"%}
  {% include figure.html image="/images/opening.jpg" caption="Ader Lab opened August 1, 2024!"%}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
