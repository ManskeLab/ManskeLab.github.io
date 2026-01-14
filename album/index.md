---
title: Album
nav:
  order: 4
  tooltip: Lab photos
---

# {% include icon.html icon="fa-solid fa-microscope" %}Lab Album

{% include section.html %}

{%- comment -%}
PHOTOS (newest → oldest)
Add new photos ONLY here
{%- endcomment -%}

{% assign photos = "" | split: "" %}

{% assign photos = photos | push:
  {"image":"images/album/2025-12-christmas-pphoto.JPG","caption":"The Manske Lab at the 2025 McCaig Christmas Party"} %}

{% assign photos = photos | push:
  {"image":"images/album/2025-12-christmas-pphoto.JPG","caption":"Manske Lab - Home Alone Edition"} %}

{% assign photos = photos | push:
  {"image":"images/album/2025-08-hike-group-photo.jpg","caption":"2025 Lab hike at Chester Lake!"} %}

{% assign photos = photos | push:
  {"image":"images/album/2025-08-hike-rocks.jpg","caption":"Feeling on top of the world on the lab hike!"} %}

{% assign photos = photos | push:
  {"image":"images/album/2025-08-hike-squad.jpg","caption":"Lab hikes rock (pun intended)"} %}

{% assign photos = photos | push:
  {"image":"images/album/2025-01-xski_3.jpg","caption":"Cross country ski day 2025"} %}

{% assign photos = photos | push:
  {"image":"images/album/2025-01-xski_1.jpg","caption":"Cross country ski day 2025"} %}

{% assign photos = photos | push:
  {"image":"images/album/2025-01-xski_2.jpg","caption":"Cross country ski day 2025"} %}

{% assign photos = photos | push:
  {"image":"images/album/2024-12-christmasdoor.jpg","caption":"McCaig christmas door contest 2024"} %}

{% assign photos = photos | push:
  {"image":"images/album/2024-08-symposium.jpg","caption":"Peak lab productivity during summer student talks"} %}

{% assign photos = photos | push:
  {"image":"images/album/2024-06-labhike_2.jpg","caption":"Lab hike 2024"} %}

{% assign photos = photos | push:
  {"image":"images/album/2024-06-labhike_3.jpeg","caption":"Lab hike 2024"} %}

{% assign photos = photos | push:
  {"image":"images/album/2024-06-labhike_1.jpg","caption":"Lab hike 2024"} %}

{% assign photos = photos | push:
  {"image":"images/album/2024-04-BMEG_formal.png","caption":"BMEG spring formal 2024"} %}

{% assign photos = photos | push:
  {"image":"images/album/2023-12-christmas.jpg","caption":"McCaig christmas party 2023"} %}

{% assign photos = photos | push:
  {"image":"images/album/2023-12-tadiwa_defense.jpg","caption":"Dinner after Tadiwa's defense 2023"} %}

{% assign photos = photos | push:
  {"image":"images/album/2023-12-christmasdoor.jpg","caption":"McCaig christmas door contest 2023"} %}

{% assign photos = photos | push:
  {"image":"images/album/2023-10-justen_abbme.jpg","caption":"Justen's AB-BME poster 2023"} %}

{% assign photos = photos | push:
  {"image":"images/album/2023-01-ski.jpg","caption":"Lab ski day 2023"} %}

{% assign photos = photos | push:
  {"image":"images/album/2022-06-labhike_3.jpeg","caption":"Lab hike 2022"} %}

{% assign photos = photos | push:
  {"image":"images/album/2022-06-labhike_2.jpeg","caption":"Lab hike 2022"} %}

{% assign photos = photos | push:
  {"image":"images/album/2022-01-nacob.jpeg","caption":"Nacob 2022"} %}

{% assign photos = photos | push:
  {"image":"images/album/2021-01-qmski.jpeg","caption":"QMSKI 2021"} %}

{% assign photos = photos | push:
  {"image":"images/album/2021-01-lab_run.jpeg","caption":"Lab run 2021"} %}

{% assign photos = photos | push:
  {"image":"images/album/2021-01-ski.jpeg","caption":"Lab ski day 2021"} %}

{% assign photos = photos | push:
  {"image":"images/album/2021-01-climbing.jpeg","caption":"Bouldering 2021"} %}

{%- comment -%}
AUTO-COLUMNS
{%- endcomment -%}

{% capture col1 %}
{% for photo in photos %}
{% if forloop.index0 | modulo: 2 == 0 %}
{% include figure.html image=photo.image caption=photo.caption %}
{% endif %}
{% endfor %}
{% endcapture %}

{% capture col2 %}
{% for photo in photos %}
{% if forloop.index0 | modulo: 2 == 1 %}
{% include figure.html image=photo.image caption=photo.caption %}
{% endif %}
{% endfor %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}
