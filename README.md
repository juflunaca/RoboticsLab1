# Laboratorio 1 - Robótica Industrial No. 1

### Por: Sebastian Campiño Figueroa, Julián Felipe Luna Castro y Diego Fernando Mejía Hernández

Este repositorio contiene las memorias y programas desarrolladas durante la primera practica de laboratorio de la materia Robotica. Esta practica esta orientada a aprender a manejar el manipulador *ABB IRB 140* en el espacio del laboratorio *LabSIR* con el controlador *ABB IRC5*. El objetivo planteado es lograr escribir las iniciales de los miembros del equipo de trabajo (D S J) con un marcador en un tablero inclinado, haciendo uso de una herramienta de diseño libre acoplada al manipulador y definiendo las trayectorias en *Robot Studio*.

## Requerimientos
* Robot Studio versión 5 o superior
* Hoja de datos del manipulador industrial IRB 140
* Software CAD (OnShape y AutoDesk Inventor)
* Manipuladores industriales ABB IRB 140
* Controlador ABB IRC5
* Herramienta

## Diseño de la herramienta
La herramienta se diseño partir de tubos de PVC de 1/2", acoples de PVC (codos y Ts) y una base impresa en 3D que sirve de acople a la brida del manipulador, todo esto unido a presion y por un tornillo M8 de 35mm de largo. Para la punta de la herramienta se utilizo un marcador sharpie y se añadieron resortes para evitar daño por colision y lograr una mejor escritura en superficies desiguales. En la siguiente imagen podemos ver un render del modelo realizado en el programa en linea *OnShape* (https://cad.onshape.com/). 

<p align="center"><img src="./images/toolRender.png" width=60%></p>

Esta herramienta es simetrica respecto al plano *X-Z*, no está alineada con el eje de la muñeca del manipulador (lo cual deberia ayudar a evitar singularidades) y el tcp esta rotado 45&deg; con respecto al eje *y*. A continuación podemos observar algunas imagenes del manipulador con la herramienta ya montada.

<p align="center"><img src="./images/MontajeDeLaHerramienta.jpeg" width=60%></p>

<p align="center"><img src="./images/DefinicionDelWorkObject.jpeg" width=60%></p>

## Importar a Robot Studio:

## Video Simulación:

<video align="center" width="320" height="240" controls>
  <source src="./video/RobotStudioSim.mp4" type="video/mp4">
</video>