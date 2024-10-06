---
title: Photos
nav:
  order: 4
  tooltip: Photos from the lab!
---

{% capture content %}
  {% include opening.jpg %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
