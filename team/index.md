---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a group of researchers working on several branches of physics and related sciences. We seek to create connections between the academic world and the community through research projects and outreach activities. We believe that by promoting research and developing outreach projects between the Ecuadorian academia and its international counterpart we can promote the study of physics and other basic sciences in Ecuador.

_Somos un grupo conformado por investigadores trabajando en diversas ramas de la física y otras ciencias afines. Buscamos crear conexiones entre el mundo académico y la comunidad a través de proyectos de investigación y jornadas de divulgación científica. Creemos que a través de proyectos de vinculación entre la academia ecuatoriana e internacional podremos promover el estudio de la física y fortalecer la ciencia básica en Ecuador._

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.png" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
