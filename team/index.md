---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our project recently established in 2024 from seedcorn funding of FAILSAFE (Fungal AMR Innovations for LMICS: Solutions and Access For Everyone). We work with a wide range of outstanding groups from microbiologists, mycologists, and bioinformaticians. <br>

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

{:.center}
We are recruiting more collaborator, please contact us!!!

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
