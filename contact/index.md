---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The Miranda Lab is based at SciLifeLab Campus Solna, one of Europe's leading centers for life science research. We are affiliated with the Division of Computational Science and Technology at KTH Royal Institute of Technology and collaborate closely with researchers across the SciLifeLab ecosystem. Our research is highly interdisciplinary and involves partnerships with academic and clinical collaborators in Sweden and around the world.

{%
  include button.html
  type="email"
  text="miranda.researchlab@gmail.com"
  link="miranda.researchlab@gmail.com"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/SciLifeLab/@59.350457,18.0234315,17z/data=!3m1!4b1!4m6!3m5!1s0x465f9d9c044c1fe5:0xfff6f935131557c1!8m2!3d59.350457!4d18.0234315!16s%2Fm%2F0gttbz2?entry=ttu&g_ep=EgoyMDI2MDYwMS4wIKXMDSoASAFQAw%3D%3D"
%}

{% comment %}
{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

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
{% endcomment %}
