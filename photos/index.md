---
title: Photos
nav:
  order: 4
  tooltip: Photos from the lab!
---

{% capture content %}
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
