# actividad4
<br>
<br>
Se agregó el juego Cannon.py (Tiro Parabólico).
<br>
<br>
## Cambio: el juego nunca termina.

Antes 'move()' se detenía cuando un objetivo salía de la ventana por la izquierda, porque el bloqu 'if not inside(target): return' no volvía a programar 'ontimer'. Ahora, al salir un objetivo, reaparece en el borde derecho con una altura aleatoria, y 'ontimer(move, 50)' se ejecuta siempre, así que el juego continúa indefinidamente.

