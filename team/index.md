---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is composed of several star students under the guidance of Professor Konstantinos (Kostas) N. Plataniotis. We include a snapshot of our current lab members below. Refer to our legacy page for more information.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: org" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|org$)"%}
