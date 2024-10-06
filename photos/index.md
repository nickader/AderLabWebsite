---
title: Photos
nav:
  order: 4
  tooltip: Photos from the lab!
---

  {% capture content %}
  {% include figure.html image="opening.jpg" caption="Ader Lab opened August 1, 2024!"%}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
