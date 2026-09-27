# Práctica · Semana 2: Búsqueda no informada en Python

**Tipo:** práctica autónoma, no calificable
**Tiempo estimado:** 2 horas
**Archivo:** [`practica-02-busqueda-no-informada.ipynb`](practica-02-busqueda-no-informada.ipynb)
**Herramientas:** Google Colab o Jupyter; ver [`complementos/herramientas.md`](../complementos/herramientas.md)
**Relación con el capítulo:** secciones 2.3 a 2.8

## Propósito

Ejecutar, modificar y comparar los algoritmos de búsqueda no informada del capítulo sobre tres problemas de García Serrano (2016, caps. 2 y 3):

| Problema | Qué se busca | Algoritmos |
|---|---|---|
| Puzle lineal de 4 piezas | Ordenar las piezas con intercambios de piezas contiguas | BFS y DFS |
| Vuelos entre ciudades españolas | La ruta con el mínimo número de trasbordos | BFS y profundidad iterativa |
| Carreteras entre ciudades españolas | La ruta con el menor número de kilómetros | BFS y coste uniforme |

El código adapta a Python 3 los listados 3-2 a 3-13 del libro, que están escritos en Python 2. Todas las celdas se probaron con Python 3.

## Cómo abrir el cuaderno

**Opción 1. Google Colab (recomendada, no requiere instalación)**
1. Descarga el archivo `.ipynb` de esta carpeta.
2. Entra a https://colab.research.google.com con tu cuenta de Google.
3. Elige *Archivo → Subir cuaderno* y selecciona el archivo.

**Opción 2. Jupyter en tu computador**
Si ya tienes Python 3 y Jupyter instalados, abre el archivo con `jupyter notebook` o desde Visual Studio Code.

## Contenido

1. La estructura de datos `Nodo`.
2. Puzle lineal con BFS y DFS. **Ejercicio 1:** amplitud contra profundidad en los 24 estados iniciales.
3. Vuelos con BFS, profundidad limitada y profundidad iterativa. **Ejercicio 2:** una ruta que el programa no encuentra, y por qué.
4. Carreteras con BFS y coste uniforme, con traza paso a paso. **Ejercicios 3 y 4:** seguir la traza, y UCS con costes iguales.
5. La explosión combinatoria. **Ejercicio 5:** puzle de *n* piezas.
6. Tabla de cierre comparando los cuatro algoritmos.

## Qué llevar a la sesión sincrónica

Tu cuaderno con las celdas ejecutadas y las respuestas de los ejercicios 1 a 5, y la tabla de cierre. Discutiremos en grupo los ejercicios 2 y 3, que muestran dos detalles del libro que conviene revisar con cuidado.

> Esta práctica no se califica, pero es la base de la parte de modelado e implementación de la [Actividad Evaluativa 1](../../actividades-evaluativas/ae1-modelado-busqueda/), que se entrega esta semana.
