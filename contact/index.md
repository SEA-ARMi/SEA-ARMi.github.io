---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

SEA-ARMi is under [Nat Pombubpa Lab](http://www.natpombubpa-lab.github.io), which is part of the [Department of Microbiology](http://www.micro.sc.chula.ac.th/index.php/en/), [Faculty of Science](https://web.sc.chula.ac.th/), [Chulalongkorn University](https://www.chula.ac.th/), Bangkok, Thailand. We are located at the 20th floor of Maha Vajirunhis Building.

{%
  include button.html
  type="email"
  text="Nuttapon.Po@chula.ac.th"
  link="Nuttapon.Po@chula.ac.th"
%}
{%
  include button.html
  type="phone"
  text="(02)-218-7155"
  link="+6622187155"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/3deoeW5ZrVQ6NX7aA"
%}

## <i class="fas fa-map-marked fa-sm"></i>Mailing Address

{:.center}
Department of Microbiology, Faculty of Science, Chulalongkorn University, 
Phayathai Rd, Wang Mai, Pathum Wan District, Bangkok 10330 

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
