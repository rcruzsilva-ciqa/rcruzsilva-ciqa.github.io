---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

## Únete

#### Estamos buscando estudiantes de prácticas, licenciatura, maestría y doctorado

Aquí puedes encontrar todo lo necesario para aprender de polímeros y desarrollar tu tema de tesis. Tengo experiencia trabajando en varios temas.

Requisitos:
- Tiempo disponible.
- Gusto por la ciencia.
- Deseo de adquirir nuevas habilidades analíticas.
- Dispuesto a recibir retroalimentación.

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Temas de interés

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/GaleriaA.jpg"
  link1="https://nasa.gov/"
  tooltip1="Dinámica molecular"

  image2="images/GaleriaB.jpg"
  link2="https://nasa.gov/"
  tooltip2="Membranas poliméricas"

  image3="images/GaleriaC.jpg"
  link3="https://nasa.gov/"
  tooltip3="Síntesis enzimática"

  image4="images/GaleriaD.jpg"
  link4="https://nasa.gov/"
  tooltip4="Compósitos"

  image5="images/GaleriaE.jpg"
  link5="https://nasa.gov/"
  tooltip5="Polímeros conductores"

  image6="images/GaleriaF.jpg"
  link6="https://nasa.gov/"
  tooltip6="Nanomateriales de carbono"
%}
