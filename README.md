# KDJ Orienta
## Problematica
Los estudiantes de primer ingreso suelen enfrentar grandes dudas por la falta de orientación al iniciar su carrera universitaria. Esto genera confusión sobre la estructura de la carrera, horarios, materias, trámites y funcionamiento general de la institución.
La ausencia de una fuente centralizada y clara de información provoca desinformación, estrés y dificultades en la adaptación académica.

## Objetivo
Desarrollar un sitio web informativo que brinde orientación clara y organizada a estudiantes de nuevo ingreso, facilitando su adaptación a la vida universitaria mediante información relevante y accesible.

## Roles del equipo.
Project Manager: Kevin David Carmona Rivera
Desarrollador Front 1: Diego Rivera Macias
Desarrollador Front 2: Jose Maria Rojas Sorcia

## Conflicto generado
El conflicto ocurrió porque dos integrantes del equipo modificaron el mismo párrafo de la descripción principal en ramas diferentes. Al intentar hacer merge hacia la rama main, Git detectó cambios incompatibles en el mismo bloque de código.

## Cómo lo resolvimos
Primero identificamos el archivo en conflicto usando git status.
Después abrimos el archivo en VS Code y analizamos ambas versiones del texto.
De forma colaborativa decidimos dejar la version del integranteA.
Posteriormente eliminamos las marcas de conflicto (<<<<<<<, =======, >>>>>>>), guardamos el archivo y realizamos:
git add .
git commit -m "Conflicto resuelto colaborativamente en descripcion principal"

## Qué aprendimos
Aprendimos cómo Git detecta conflictos cuando dos ramas modifican la misma sección de un archivo, la importancia de la comunicación en el equipo y el proceso correcto para resolver conflictos de forma colaborativa sin perder información.
