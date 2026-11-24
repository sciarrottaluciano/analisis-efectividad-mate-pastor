# Análisis de la efectividad del Mate Pastor

![Dashboard del análisis](documentacion/dashboard.png)

Este proyecto analiza la efectividad del Mate Pastor en partidas reales de ajedrez,
con un enfoque empírico basado en datos.

A partir de 6,2 millones de partidas jugadas en Lichess.org durante julio de 2016, el análisis
se centra en la tasa de éxito del Mate Pastor cuando lo juegan las blancas, segmentada por
rangos de ELO.

El proyecto incluye la limpieza de datos, reglas de clasificación para identificar los
intentos válidos y una visualización construida en Power BI.

## Principales resultados

- El Mate Pastor tiene una efectividad del 4,4 %: funciona en 1 de cada 23 intentos.
- La efectividad cae del 7,0 % en ELO 1000 al 3,2 % en ELO 1700.
- Cuando el ataque se defiende, las blancas ganan solo el 45,0 % de las partidas,
  frente al 49,8 % habitual, y la ventaja pasa a las negras.

La metodología completa está disponible en la [documentación del análisis (PDF)](documentacion/analisis-efectividad-mate-pastor.pdf).
