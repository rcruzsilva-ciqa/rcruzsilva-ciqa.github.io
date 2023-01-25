---
title: Equipo
nav:
  order: 3
  tooltip: Nuestro equipo de trabajo
---

# <i class="fas fa-users"></i>Equipo

Nuestro grupo de trabajo inició en Octubre del 2022, estamos iniciando por lo que aún somos pocos pero con mucho ánimo.

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

“You teach me, I forget. You show me, I remember. You involve me, I understand.”
― Edward O. Wilson 

{% include section.html %}

## Únete

#### Estamos buscando estudiantes de prácticas, licenciatura, maestría y doctorado

Aquí puedes encontrar todo lo necesario para aprender de polímeros y desarrollar tu tema de tesis. Tengo experiencia trabajando en varios temas.

Requisitos:
- Tiempo disponible.
- Gusto por la ciencia.
- Deseo de adquirir nuevas habilidades analíticas.
- Dispuesto a recibir retroalimentación.

{% include link.html type="external" link="https://google.com/" text="Contáctanos" icon="" style="button" %}
{:.center}

{% include section.html %}

## Temas de interés

Si quieres realizar tesis en estas líneas de investigación acércate a platicar.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/GaleriaD.gif"
  link1="https://nasa.gov/"
  tooltip1="Dinámica molecular"

  image2="images/GaleryB.jpg"
  link2="https://nasa.gov/"
  tooltip2="Membranas poliméricas"

  image3="images/GaleriaC.jpg"
  link3="https://nasa.gov/"
  tooltip3="Síntesis enzimática"

  image4="images/GaleryD.gif"
  link4="https://nasa.gov/"
  tooltip4="Polímeros conductores"

  image5="images/GalerieE.gif"
  link5="https://nasa.gov/"
  tooltip5="Compósitos inteligentes"

  image6="images/GaleriaF.jpg"
  link6="https://nasa.gov/"
  tooltip6="Nanocompósitos de carbono"
%}
