---
title: KRASL
header: images/background.jpg
footer: images/background.jpg
header-dark: false
footer-dark: false
redirect_from:
  - krasl
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

<p style="text-align: center;">News and updates from the Manske lab.</p>

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}