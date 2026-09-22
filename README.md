# Air 3S Flight Planner V5

Planner web para DJI Air 3S.

## V5
- Leyenda visual para colores, H, waypoints y R.
- Pronóstico Open-Meteo a 10, 80 y 120 m.
- Interpolación vectorial del viento para la altitud real de cada tramo.
- Comparador de altitudes y sugerencia de la altitud que deja mayor margen de batería dentro del límite básico aplicable.
- No se inventa una mejora de O4 por altitud: DJI no publica una curva O4↔altura y la app no tiene un modelo 3D fiable de obstáculos.
- Guardado local del perfil meteorológico.

La batería es una estimación de planificación anclada a ensayos publicados por DJI, no una garantía ni un sustituto de la telemetría de DJI Fly. Open-Meteo aporta pronóstico meteorológico modelado, no una medición local en vivo.