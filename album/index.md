---
title: Album
nav:
  order: 4
  tooltip: Lab photos
---

# {% include icon.html icon="fa-solid fa-microscope" %}Lab Album

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/album/2025-01-xski_3.jpg"
  caption="xski_3"
%}

{%
  include figure.html
  image="images/album/2025-01-xski_1.jpg"
  caption="xski_1"
%}

{%
  include figure.html
  image="images/album/2024-08-symposium.jpg"
  caption="symposium"
%}

{%
  include figure.html
  image="images/album/2024-06-labhike_2.jpg"
  caption="labhike_2"
%}

{%
  include figure.html
  image="images/album/2024-04-BMEG_formal.png"
  caption="BMEG_formal"
%}

{%
  include figure.html
  image="images/album/2023-12-christmas.jpg"
  caption="christmas"
%}

{%
  include figure.html
  image="images/album/2023-10-justen_abbme.jpg"
  caption="justen_abbme"
%}

{%
  include figure.html
  image="images/album/2022-06-labhike_3.jpeg"
  caption="labhike_3"
%}

{%
  include figure.html
  image="images/album/2022-01-nacob.jpeg"
  caption="nacob"
%}

{%
  include figure.html
  image="images/album/2021-01-qmski.jpeg"
  caption="qmski"
%}

{%
  include figure.html
  image="images/album/2021-01-lab_run.jpeg"
  caption="lab_run"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/album/2025-01-xski_2.jpg"
  caption="xski_2"
%}

{%
  include figure.html
  image="images/album/2024-12-christmasdoor.jpg"
  caption="christmasdoor"
%}

{%
  include figure.html
  image="images/album/2024-06-labhike_3.jpg"
  caption="labhike_3"
%}

{%
  include figure.html
  image="images/album/2024-06-labhike_1.jpg"
  caption="labhike_1"
%}

{%
  include figure.html
  image="images/album/2023-12-tadiwa_defense.jpg"
  caption="tadiwa_defense"
%}

{%
  include figure.html
  image="images/album/2023-12-christmasdoor.jpg"
  caption="christmasdoor"
%}

{%
  include figure.html
  image="images/album/2023-01-ski.jpg"
  caption="ski"
%}

{%
  include figure.html
  image="images/album/2022-06-labhike_2.jpeg"
  caption="labhike_2"
%}

{%
  include figure.html
  image="images/album/2021-01-ski.jpeg"
  caption="ski"
%}

{%
  include figure.html
  image="images/album/2021-01-climbing.jpeg"
  caption="climbing"
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
