# Práctica · Semana 1: Laboratorio de capacidades de la IA

**Tipo:** práctica autónoma, no calificable
**Tiempo estimado:** 90 minutos
**Herramientas:** ver [`complementos/herramientas.md`](../complementos/herramientas.md)
**Relación con el capítulo:** secciones 1.1.3, 1.2 y 1.6

## Propósito

Observar de primera mano qué pueden y qué no pueden hacer algunos sistemas de IA, y aprender a describirlos con los conceptos del capítulo: las capacidades de la prueba de Turing, el esquema REAS y las propiedades del entorno.

Crea un archivo `practica-semana-01.md` en tu computador (o un documento de texto) para ir registrando tus respuestas. Llévalo a la sesión sincrónica.

---

## Parte A. Una IA que «ve» (25 min)

1. Entra a **Quick, Draw!** y juega una ronda completa (6 dibujos).
2. Registra en una tabla:

   | Objeto pedido | ¿Lo adivinó? | ¿En cuántos segundos? | ¿Qué otras cosas creyó ver? |
   |---|:-:|:-:|---|
   | | | | |

3. Abre **AutoDraw**, haz un trazo sencillo (una casa, un gato, una bicicleta) y observa las sugerencias.
4. Responde:
   - ¿Qué capacidad de la sección 1.1.3 están usando estas herramientas: ver, oír o entender?
   - Quick, Draw! reúne los dibujos de sus jugadores en un gran conjunto de datos. Según lo que leíste sobre los tipos de aprendizaje automático, ¿por qué crees que la herramienta necesita saber qué objeto *se pidió* dibujar?
   - ¿En qué casos se equivocó? ¿Qué te dice eso sobre los límites de la IA estrecha (sección 1.5)?

## Parte B. Tres agentes a tu alrededor (35 min)

1. Elige tres sistemas con IA que uses con frecuencia (por ejemplo: el filtro de *spam* de tu correo, una aplicación de navegación, un asistente de voz, las recomendaciones de una plataforma de video).
2. Para cada uno, completa la descripción REAS (sección 1.6.3):

   | Sistema | Rendimiento | Entorno | Actuadores | Sensores |
   |---|---|---|---|---|
   | | | | | |

3. Clasifica el entorno de uno de ellos según las seis dimensiones de la tabla 1.5 y justifica cada respuesta en una línea.
4. ¿Qué tipo de agente crees que es cada uno (sección 1.6.5)? No hay una única respuesta correcta: lo importante es tu justificación.

## Parte C. Pon a prueba a ELIZA (30 min)

1. Conversa durante 10 minutos con **ELIZA**. Escribe en inglés, que es el idioma de este programa.
2. Intenta descubrir cómo «piensa»: repite frases, cambia de tema bruscamente, hazle preguntas concretas sobre el mundo.
3. Luego haz las mismas preguntas a un asistente conversacional actual basado en un LLM (el que uses normalmente).
4. Completa la tabla usando las capacidades de la prueba de Turing (sección 1.2.2):

   | Capacidad | ELIZA | Asistente actual | Evidencia (copia un fragmento breve de la conversación) |
   |---|:-:|:-:|---|
   | Procesamiento del lenguaje natural | | | |
   | Representación del conocimiento | | | |
   | Razonamiento automático | | | |
   | Aprendizaje automático | | | |

5. Responde en un párrafo: ¿alguno de los dos te hizo dudar de si hablabas con una máquina? ¿Qué te dice eso sobre la advertencia de Russell y Norvig acerca de imitar a los humanos (sección 1.2.3)?

---

## Para la sesión sincrónica

Lleva tus tablas y tus respuestas. Discutiremos en grupo los errores más curiosos de Quick, Draw! y las diferencias entre ELIZA y los asistentes actuales.

> Esta práctica no se califica, pero te prepara para la [Actividad Evaluativa 1](../../actividades-evaluativas/ae1-modelado-busqueda/), en la que describirás y modelarás un problema de IA.
