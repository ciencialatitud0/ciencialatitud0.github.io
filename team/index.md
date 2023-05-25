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

## External collaborators

We appreciate the collaboration of the following researchers:

_Agradecemos la colaboración de los siguientes investigadores:_

 * Luz Ángela García, Universidad ECCI, Colombia
 * Daniel Čapek, University of Konstanz, Germany
 * Genevieve Shattow, ThroughPut.ai, United States
 * Diego Morales, Yachay Tech University, Ecuador
 * María José Benítez, Escuela Politécnica Nacional, Ecuador
 * Maximilian Menger, University of Groningen, The Netherlands
 * Mayra Pallaroso, SOLCA Quito, Ecuador
 * Albert Thie, University of Groningen, The Netherlands
 * Cristina Mantilla, Fermilab, United States
 * Oscar Chimborazo, Yachay Tech University, Ecuador
 * Cloé Girard-Carillo, Johannes Gutenberg University, Mainz, Germany
 * Jorge Ontaneda, Queen Mary University of London, United Kingdom
 * Sylvain Vanneste, Laboratoire de l'Accélérateur Linéaire, France
 * Leonardo Basile, Escuela Politécnica Nacional, Ecuador

{% include section.html %}

{% capture content %}

## Institutions

We thank the collaboration and sponsorship of the following institutions:

{% include figure.html image="images/ICTP.svg" link="https://www.ictp.it/" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
