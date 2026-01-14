---
title: Album
nav:
  order: 4
  tooltip: Lab photos
---

# {% include icon.html icon="fa-solid fa-microscope" %}Lab Album

{% include section.html %}

{%- comment -%}
PHOTO LIST
Add new photos at the TOP
Newest → Oldest
{%- endcomment -%}

{% assign photos = "" | split: "" %}

{% assign photos = photos | push:
  "images/album/2025-12-christmas-pphoto.JPG||The Manske Lab at the 2025 McCaig Christmas Party" %}

{% assign photos = photos | push:
  "images/album/2025-12-christmas-pphoto.JPG||Manske Lab - Home Alone Edition" %}

{% assign photos = photos | push:
  "images/album/2025-08-hike-group-photo.jpg||2025 Lab hike at Chester Lake!" %}

{% assign photos = photos | push:
  "images/album/2025-08-hike-rocks.jpg||Feeling on top of the world on the lab hike!" %}

{% assign photos = photos | push:
  "images/album/2025-08-hike-squad.jpg||Lab hikes rock (pun intended)" %}

{% assign photos = photos | push:
  "images/album/2025-01-xski_3.jpg||Cross country ski day 2025" %}

{% assign photos = photos | push:
  "images/album/2025-01-xski_1.jpg||Cross country ski day 2025" %}

{% assign photos = photos | push:
  "images/album/2025-01-xski_2.jpg||Cross country ski day 2025" %}

{% assign photos = photos | push:
  "images/album/2024-12-christmasdoor.jpg||McCaig christmas door contest 2024" %}

{% assign photos = photos | push:
  "images/album/2024-08-symposium.jpg||Peak lab productivity during summer student talks" %}

{% assign photos = photos | push:
  "images/album/2024-06-labhike_2.jpg||Lab hike 2024" %}

{% assign photos = photos | push:
  "images/album/2024-06-labhike_3.jpeg||Lab hike 2024" %}

{% assign photos = photos | push:
  "images/album/2024-06-labhike_1.jpg||Lab hike 2024" %}

{% assign photos = photos | push:
  "images/album/2024-04-BMEG_formal.png||BMEG spring formal 2024" %}

{% assign photos = photos | push:
  "images/album/2023-12-christmas.jpg||McCaig christmas party 2023" %}

{% assign photos = photos | push:
  "images/album/2023-12-tadiwa_defense.jpg||Dinner after Tadiwa's defense 2023" %}

{% assign photos = photos | push:
  "images/album/2023-12-christmasdoor.jpg||McCaig christmas door contest 2023" %}

{% assign photos = photos | push:
  "images/album/2023-10-justen_abbme.jpg||Justen's AB-BME poster 2023" %}

{% assign photos = photos | push:
  "images/album/2023-01-ski.jpg||Lab ski day 2023" %}

{% assign photos = photos | push:
  "images/album/2022-06-labhike_3.jpeg||Lab hike 2022" %}

{% assign photos = photos | push:
  "images/album/2022-06-labhike_2.jpeg||Lab hike 2022" %}

{% assign photos = photos | push:
  "images/album/2022-01-nacob.jpeg||Nacob 2022" %}

{% assign photos = photos | push:
  "images/album/2021-01-qmski.jpeg||QMSKI 2021" %}

{% assign photos = photos | push:
  "images/album/2021-01-lab_run.jpeg||Lab run 2021" %}

{% assign photos = photos | push:
  "images/album/2021-01-ski.jpeg||Lab ski day 2021" %}

{% assign photos = photos | push:
  "images/album/2021-01-climbing.jpeg||Bouldering 2021" %}
{%- comment -%}
AUTO-GENERATED COLUMNS (GitHub Pages safe)
{%- endcomment -%}

{% capture col1 %}
{% for photo in photos %}
  {% assign parts = photo | split: "||" %}
  {% assign image = parts[0] %}
  {% assign caption = parts[1] %}

  {% if forloop.index0 | modulo: 2 == 0 %}
    {% include figure.html image=image caption=caption %}
  {% endif %}
{% endfor %}
{% endcapture %}

{% capture col2 %}
{% for photo in photos %}
  {% assign parts = photo | split: "||" %}
  {% assign image = parts[0] %}
  {% assign caption = parts[1] %}

  {% if forloop.index0 | modulo: 2 == 1 %}
    {% include figure.html image=image caption=caption %}
  {% endif %}
{% endfor %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
