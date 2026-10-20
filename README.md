# Desarrollo Orientado por Objetos - Proyecto Inicial

## Descripción

Este repositorio contiene el desarrollo del proyecto inicial de la asignatura **Desarrollo Orientado por Objetos (DOPO)**.

El proyecto consiste en desarrollar un simulador inspirado en el problema **Slot Machine** de la maratón internacional de programación 2025. Su desarrollo aplica conceptos de programación orientada a objetos, diseño de software, pruebas y desarrollo incremental.

El proyecto está organizado en cuatro ciclos, lo que permite realizar un seguimiento de la evolución del simulador, sus funcionalidades, diseños, pruebas y documentación a lo largo de cada etapa.

## Estructura del repositorio

/
├── README.md
│
├── Ciclo-1/
│   ├── README.md
│   ├── Código fuente/
│   ├── Diagrama de clases - SlotMachine.asta
│   └── Diagrama de secuencia - SlotMachine.asta
│
├── Ciclo-2/
│   ├── README.md
│   ├── CICLO 2 SLOTMACHINE.asta
│   ├── Diagrama de clases - SlotMachine (1).asta
│   ├── Parte numero 4.docx
│   └── SlotMachine.zip
│
├── Ciclo-3/
│   ├── README.md
│   ├── CLASES SLOTMACHINE 3.asta
│   ├── SECUENCIA SLOTMACHINE 3.asta
│   ├── RETROPECTIVA.pdf
│   ├── pruebas_aceptacion.pdf
│   └── SlotMachine_Ciclo3.zip
│
└── Ciclo-4/
    ├── README.md
    ├── CICLO 4 DS.asta
    ├── CLASES SLOTMACHINE 4.asta
    ├── SlotMachine_Ciclo4.zip
    ├── Pruebas_aceptacion_Ciclo_4.pdf
    └── retrospectiva ciclo 4.pdf

> La estructura anterior es una referencia de organización. Los nombres deben coincidir con los archivos que estén realmente publicados en el repositorio.

## Ciclos del proyecto

### Ciclo 1 - Construcción inicial

En el primer ciclo se desarrolló una primera versión funcional del simulador **SlotMachine**.

Los principales objetivos fueron construir la máquina tragamonedas, administrar sus ruedas y símbolos, permitir su funcionamiento y consultar su configuración.

Entre los productos desarrollados se encuentran:

- Código fuente del simulador.
- Diagrama de clases elaborado en Astah.
- Diagramas de secuencia.
- Implementación en Java utilizando BlueJ.

Para consultar los productos y la información detallada, diríjase a la carpeta `Ciclo-1`.

### Ciclo 2 - Refactoring y extensión

En el segundo ciclo se amplió la funcionalidad del simulador mediante nuevas operaciones para administrar y controlar las ruedas.

Las principales funcionalidades incorporadas fueron:

- Intercambiar dos ruedas.
- Fijar y soltar una rueda.
- Rotar una rueda un número determinado de pasos.
- Establecer la máquina en una configuración específica.

También se trabajó en el diseño del sistema y en las pruebas unitarias y de aceptación correspondientes a esta etapa.

Los productos de este ciclo se encuentran en la carpeta `Ciclo-2`.

### Ciclo 3 - Refactoring y extensión

En el tercer ciclo se amplió el proyecto para abordar la solución del problema de la maratón **Slot Machine** y la simulación de las acciones necesarias para obtener una configuración ganadora, cuando sea posible.

Los principales objetivos fueron:

- Crear una máquina con igual número de ruedas y símbolos.
- Implementar la solución del problema mediante la clase `SlotMachineContest`.
- Simular la solución obtenida.
- Desarrollar pruebas unitarias y pruebas de aceptación.
- Actualizar los diagramas de diseño y la documentación del proyecto.

Durante este ciclo también se estableció que la máquina debe permanecer invisible durante la resolución del problema y visible durante la simulación.

Los productos de esta etapa se encuentran en la carpeta `Ciclo-3`.

### Ciclo 4 - Refactoring y extensión

En el cuarto ciclo se extendió el simulador para manejar diferentes tipos de ruedas y símbolos, aplicando el principio de **extensibilidad** del diseño orientado a objetos.

Las funcionalidades incorporadas fueron:

- **Rueda `lefty`:** cuando tiene una rueda a su izquierda, copia el estado de esa rueda al girar.
- **Rueda `rebel`:** no permite ser bloqueada, intercambiada ni eliminada.
- **Símbolo `ephemeral`:** reduce su tamaño cada vez que es seleccionado, hasta alcanzar el tamaño mínimo definido por la implementación.
- **Símbolo `shy`:** alterna entre visible e invisible cada vez que es seleccionado.
- **Símbolo `glowing`:** nuevo tipo de símbolo propuesto por el equipo, que alterna su color actual entre azul y amarillo al ser seleccionado.

Además, se conservaron los comportamientos de los tipos normales de ruedas y símbolos.

En esta etapa se trabajó en:

- Extender la implementación de Java para incorporar los nuevos tipos.
- Actualizar el diseño y los diagramas de clases en Astah.
- Desarrollar pruebas unitarias para los comportamientos nuevos.
- Preparar pruebas de aceptación para verificar el funcionamiento de las nuevas ruedas y símbolos.
- Documentar los resultados y la retrospectiva del ciclo.

La guía también establece que los elementos de diferentes tipos deben poder distinguirse claramente de forma visual.

Los productos de esta etapa se encuentran en la carpeta `Ciclo-4`.

## Tecnologías y herramientas utilizadas

- **Java:** implementación del proyecto.
- **BlueJ:** desarrollo, compilación y ejecución del código y las pruebas.
- **Astah:** elaboración y actualización de los diagramas de clases y secuencia.
- **JUnit:** ejecución de las pruebas unitarias del proyecto.
- **Git y GitHub:** control de versiones, publicación y organización de los productos del proyecto.
- **PDF y Markdown:** documentación de las pruebas de aceptación, retrospectivas y entregas.

## Pruebas y documentación

Durante los ciclos se desarrollaron pruebas y documentos para verificar el comportamiento del simulador y registrar su evolución.

Entre los productos de documentación se incluyen:

- Diagramas de clases y de secuencia.
- Pruebas unitarias de las funcionalidades implementadas.
- Pruebas de aceptación preparadas para las presentaciones.
- Documentos de retrospectiva de los ciclos.
- Archivos README para describir la organización y los resultados de cada entrega.

En particular, para el Ciclo 4 se incluyen las pruebas de `SlotMachineC4Test` y `SlotMachineCC4Test`, junto con las pruebas de aceptación de los tipos `lefty`, `rebel`, `ephemeral`, `shy` y `glowing`.

## Organización del proyecto

Cada ciclo cuenta con su propia carpeta, que contiene los productos de diseño, implementación y documentación correspondientes a esa etapa.

Esta organización permite conservar la evolución del simulador, consultar las entregas anteriores y revisar las funcionalidades incorporadas durante el desarrollo incremental.

## Integrantes

- Laura Valentina Fonseca
- Santiago Rojas Gomez

## Asignatura

**Asignatura:** Desarrollo Orientado por Objetos - DOPO

**Proyecto:** Proyecto Inicial - SlotMachine

**Periodo:** 2026-2
