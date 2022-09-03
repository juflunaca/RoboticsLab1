# RoboticsLab1
Descripción de la solución:

Se diseña a partir de tubos de PVC de 3cm de diámetro, acoples de PVC, la impresión de una brida con PLA blanco, un resorte y un marcador Sharpie una herramienta con una orientación de 45° en el eje y respecto al TCP del plato porta herramienta con las dimensiones y geometrías presentadas en este repositorio, además se modela el tablero con las letras a dibujar, en este caso las letras D, S y J mayúsculas y la letra Phi debido a que es la que representa a nuestra facultad.
En robot studio se importa la herramienta y el tablero, se ubican en el plato portaherramientas (Articulación 6) del robot y en el suelo respectivamente,  se definen las orientaciones y TCPs, se generan las trayectorias (Paths) para cada letra, se definen las distancias de aproximación para cada letra, se definen dos puntos (JoinTargets) para ser los puntos Home y el punto de acercamiento, se define un Jerk z=10 y una velocidad v=200, se genera el código RAPID y se exporta el programa para poder usarlo en el robot físico.

