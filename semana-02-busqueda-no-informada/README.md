# Semana 2. Representación de problemas y búsqueda no informada

Esta semana aprendes a convertir un problema en algo que un computador pueda resolver: un modelo con estados, acciones y un objetivo. Después estudias las primeras estrategias para buscar la solución de forma sistemática, sin más información que la del enunciado. Estas estrategias son la base de la búsqueda informada (semana 3) y de los juegos (semana 4).

## Objetivos de aprendizaje

1. Definir un problema a partir de su modelo, su objetivo y su función de evaluación.
2. Reconocer problemas canónicos de la IA (viajante de comercio, SAT, programación lineal entera) y explicar por qué su tamaño crece de forma explosiva.
3. Formular un problema de búsqueda con estado inicial, acciones, test objetivo y costo del camino.
4. Representar un espacio de estados como árbol o como grafo.
5. Aplicar la búsqueda en amplitud, en profundidad (limitada e iterativa) y de coste uniforme.
6. Comparar las estrategias según su completitud, su optimalidad y su complejidad.

## Temas de la semana

- Modelo, objetivo y función de evaluación
- Tipos de problemas: viajante de comercio, SAT y programación lineal entera
- Espacio de estados: árboles y grafos
- Búsqueda en amplitud (BFS)
- Búsqueda en profundidad (DFS) y profundidad iterativa
- Búsqueda de coste uniforme
- Complejidad, completitud y optimalidad

## Ruta de estudio

| Paso | Actividad | Tiempo estimado |
|:-:|---|:-:|
| 1 | Leer el [capítulo 2](capitulo/capitulo-02-busqueda-no-informada.md) y responder los recuadros «Para pensar» | 100 min |
| 2 | Ver al menos dos [videos complementarios](complementos/videos.md) | 30-60 min |
| 3 | Explorar las visualizaciones de BFS, DFS y Dijkstra de las [herramientas](complementos/herramientas.md) | 20 min |
| 4 | Realizar la [práctica de la semana](practicas/) en Google Colab | 2 h |
| 5 | Resolver las preguntas de repaso del final del capítulo | 45 min |
| 6 | Explorar los [materiales adicionales](materiales-adicionales/) (opcional) | libre |
| 7 | Llevar tus dudas a la sesión sincrónica | 2 h |
| 8 | Terminar y entregar la [Actividad Evaluativa 1](../actividades-evaluativas/ae1-modelado-busqueda/) | según el enunciado |

## Lecturas base

- García Serrano, A. (2016). *Inteligencia artificial: Fundamentos, práctica y aplicaciones* (2.ª ed.), caps. 2 y 3, y apéndice sobre Python (consulta).
- Russell, S. J., y Norvig, P. (2004). *Inteligencia artificial: Un enfoque moderno* (2.ª ed.), cap. 3, secciones 3.1 a 3.5 (consulta).

## Práctica

**Búsqueda no informada en Python:** un cuaderno de Jupyter que adapta a Python 3 los programas de García Serrano (2016). Resolverás el puzle lineal, los vuelos con menos trasbordos y las rutas por carretera con menos kilómetros, compararás BFS, DFS, profundidad iterativa y coste uniforme, y medirás la explosión combinatoria. Ver [`practicas/README.md`](practicas/README.md).

## Sesión sincrónica

- **Fecha y hora:** *[por definir]*
- **Enlace:** Equipo de Microsoft Teams del curso
- **Agenda sugerida:** resolución en vivo de BFS y DFS sobre el grafo de vuelos (pregunta de repaso 7) · discusión de los ejercicios 2 y 3 de la práctica y de las notas de precisión del capítulo · dudas finales de la Actividad Evaluativa 1.

## Evaluación

Entrega de la **Actividad Evaluativa 1** (25 %), que abarca las semanas 1 y 2, en la tarea del Equipo de Teams. La práctica de esta semana no se califica, pero es la base de la parte de modelado e implementación de la actividad.
