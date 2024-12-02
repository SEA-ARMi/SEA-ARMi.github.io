---
title: Team
nav:
  order: 3
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# {% include icon.html icon="fa-solid fa-users" %}FAILSAFE Project Team

Our project recently established in 2024 from seedcorn funding of FAILSAFE (Fungal AMR Innovations for LMICS: Solutions and Access For Everyone). We work with a wide range of outstanding groups from microbiologists, mycologists, and bioinformaticians. <br>

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: master, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}

{% include section.html dark=true %}

{:.center}
We are recruiting more collaborator, please contact us!!!

# {% include section.html %}

#{ % capture content %}

# {% include figure.html image="images/photo.jpg" %}
# {% include figure.html image="images/photo.jpg" %}
# {% include figure.html image="images/photo.jpg" %}

# {% endcapture %}

# {% include grid.html style="square" content=content %}
