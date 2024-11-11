---
title: Photos
nav:
  order: 4
  tooltip: Photos from the lab!
---

  {% capture content %}
  {% include figure.html image="/images/halloween24.jpeg" caption="Halloween 2024! ![A group photo of 5 lab members and Nick. Nick is dressed as a Jedi with a blue lightsaber. Two other lab members are wearing customer, one as Sully from Monsters Inc. and one as a "Western" blot.]"%}
  {% include figure.html image="/images/camera.jpeg" caption="Our new microscope camera arrived! Hello 95% quantum efficency!"%}
  {% include figure.html image="/images/opening.jpg" caption="Ader Lab opened August 1, 2024!"%}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
