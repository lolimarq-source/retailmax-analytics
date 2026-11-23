# Jira — Conceptos clave

**Objetivo del módulo:** aprender una herramienta utilizada en equipos
profesionales para organizar el trabajo.

Fuente de estudio: guía de introducción a Jira de Atlassian —
https://www.atlassian.com/es/software/jira/guides/getting-started/basics

---

## ¿Qué es Jira?

Jira es la herramienta donde el equipo organiza su trabajo: todo lo que hay
que hacer vive ahí como **actividades**, se ordena en un **backlog** y se
trabaja en un **tablero** que muestra en qué estado está cada cosa. Nadie
trabaja «de memoria»: lo que no está en Jira, no existe para el equipo.

## El espacio de trabajo (el proyecto)

Es el contenedor de todo. Cada proyecto tiene su tablero, su backlog y sus
actividades, y lo comparte todo el equipo. En nuestro curso el proyecto es el
del curso (CDADIA / Power Data + AI) y dentro de él vive el trabajo de
RetailMax.

## El tablero y sus columnas

El tablero muestra las actividades como **tarjetas**. Cada columna es un
estado del trabajo, y mover la tarjeta de columna es avanzar el trabajo:

**Backlog → To Do → In Progress → Review → Done**

- **Backlog** — todo lo pendiente, esperando su turno.
- **To Do** — elegido para hacerse, todavía no empezado.
- **In Progress** — alguien lo está trabajando ahora.
- **Review** — terminado por quien lo hizo, esperando revisión.
- **Done** — revisado y aprobado. Trabajo cerrado.

## El backlog

Es la lista completa de todo lo que hay que hacer, ordenada por **prioridad**:
lo más importante arriba. De esa lista se elige qué entra a cada sprint. El
backlog nunca está vacío: a medida que el proyecto avanza, se le agregan
actividades nuevas y se reordena.

## Las actividades

Son la unidad de trabajo. Se organizan de mayor a menor:

- **Épica** — un bloque grande de trabajo (ej.: «EPIC 01 - Datos, KPIs y
  exploración»). No se hace de una vez: se divide.
- **Historia** — una parte de la épica, contada como una necesidad (ej.: una
  unidad del curso).
- **Tarea** — un trabajo concreto dentro de la historia.
- **Subtarea** — cada paso pequeño de una tarea (ej.: «mapa mental»).

Cada actividad tiene: **título**, **descripción**, **responsable** (quién la
hace), **informador** (quién la pidió o la asignó), **estado** (la columna del
tablero), **prioridad** y, cuando hace falta, **fecha de vencimiento** y
**archivos adjuntos** como evidencia.

## El sprint

Es el ciclo corto de trabajo (1 a 4 semanas). Al inicio se eligen actividades
del backlog, durante el sprint se trabajan en el tablero, y al final lo
terminado pasa a Done. Lo que no se terminó vuelve al backlog.

## Las relaciones, en una línea

El **proyecto** contiene todo → el **backlog** guarda y ordena las
**actividades** → cada sprint toma algunas → se trabajan en el **tablero**
moviéndolas por las **columnas** hasta Done.
