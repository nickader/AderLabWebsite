---
---

## Highlights

{% capture text %}

Test1

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We’re always interested in recruiting compassionate and dedicated inviduals to join our team. Please reach out to Nick on the [Contact](https://nickaderlab.com/contact/) page!

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images//uncgreensboro_v_3-color-1024x612.webp"
  link="team"
  title="Our Team"
  text=text
%}

{% include feature.html image="images/uncgreensboro_v_3-color-1024x612.webp" title="Our Team" text="We’re always interested in recruiting compassionate and dedicated inviduals to join our team. Please reach out to Nick on the [Contact](https://nickaderlab.com/contact/) page!"  %}


