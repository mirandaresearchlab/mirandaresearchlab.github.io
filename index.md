---
---

# Miranda Lab Website

We develop machine learning methods to decode cellular behavior by integrating microscopy images and omics data to simulate, predict, and understand complex biological processes. Our work bridges the gap between raw biological data and meaningful clinical impact.

{% include section.html %}

## Highlights

{% capture text %}

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
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  title="Our Publications"
  flip=true
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
