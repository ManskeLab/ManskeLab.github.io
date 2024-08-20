---
title: Projects
nav:
  order: 2
  tooltip: projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

<p style="text-align: center;">Explore what our lab is currently working on!</p>
<p style="text-align: center;">Please note some repositories are still private but might be made public in the future.</p>

<!-- {% include tags.html tags="publication, resource, website" %} -->

{% include search-info.html %}

{% include section.html %}

## Graduate Student Projects

{% include list.html component="card" data="projects" filters="group: grad_projects" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filters="group: " style="small" %}
