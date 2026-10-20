# Ciclo 4 - SlotMachine

## Descripción

Este directorio contiene los productos desarrollados durante el cuarto ciclo del proyecto inicial de la asignatura **Desarrollo Orientado por Objetos (DOPO-POOB)**.

El proyecto consiste en desarrollar un simulador inspirado en el problema *Slot Machine* de la maratón internacional de programación 2025. En este ciclo se extiende el sistema para manejar diferentes tipos de ruedas y símbolos, manteniendo el principio de extensibilidad del diseño.

## Objetivo del ciclo

El objetivo principal del cuarto ciclo fue refactorizar y extender **SlotMachine** para incorporar comportamientos especializados en ruedas y símbolos, sin perder el funcionamiento de los elementos existentes.

De acuerdo con la guía, el simulador debía permitir diferentes tipos de ruedas y símbolos. Se implementaron los tipos `lefty` y `rebel` para las ruedas, `ephemeral` y `shy` para los símbolos, y un nuevo tipo propuesto por el equipo: `glowing`.

## Funcionalidades incorporadas

- **Rueda `lefty`:** cuando tiene una rueda a su izquierda, copia el estado de esa rueda al girar.
- **Rueda `rebel`:** no permite ser bloqueada, intercambiada ni eliminada.
- **Símbolo `ephemeral`:** reduce su tamaño al ser seleccionado, hasta alcanzar el tamaño mínimo definido por la implementación.
- **Símbolo `shy`:** alterna entre visible e invisible cada vez que es seleccionado.
- **Símbolo `glowing`:** tipo nuevo propuesto por el equipo que alterna su color actual entre azul y amarillo al ser seleccionado.

También se conservan los tipos normales de ruedas y símbolos. La implementación debe permitir distinguir visualmente los distintos tipos de elementos, según el requisito de usabilidad de la guía.

## Pruebas

La entrega incluye pruebas unitarias y pruebas de aceptación para verificar los comportamientos incorporados en el ciclo.

- `SlotMachineC4Test`: pruebas unitarias del proyecto para el ciclo 4.
- `SlotMachineCC4Test`: pruebas unitarias compartidas; la guía solicita un mínimo de dos casos.
- `Pruebas_aceptacion_Ciclo_4.pdf`: documento con pruebas de aceptación para los tipos `lefty`, `rebel`, `ephemeral`, `shy` y `glowing`.

También se contemplan las suites de pruebas de ciclos anteriores para revisar que las nuevas extensiones no afecten el comportamiento previo.

## Contenido de la entrega

Los archivos principales de esta carpeta son:

- **`CICLO 4 DS.asta`:** archivo Astah con los diagramas de diseño del ciclo.
- **`CLASES SLOTMACHINE 4.asta`:** archivo Astah con el diagrama de clases actualizado para la extensión del ciclo 4.
- **`SlotMachine_Ciclo4.zip`:** implementación del proyecto en BlueJ.
- **`Pruebas_aceptacion_Ciclo_4.pdf`:** documento con las pruebas de aceptación preparadas para la presentación.
- **`retrospectiva ciclo 4.pdf`:** documento de retrospectiva del proyecto, que debe incluir este ciclo y los anteriores.
- **`README.md`:** descripción y organización de la entrega.

## Estructura

\```text
Ciclo-4/
├── README.md
├── CICLO 4 DS.asta
├── CLASES SLOTMACHINE 4.asta
├── SlotMachine_Ciclo4.zip
├── Pruebas_aceptacion_Ciclo_4.pdf
└── retrospectiva ciclo 4.pdf
\```

## Integrantes

- Laura Valentina Fonseca
- Santiago Rojas Gomez

## Proyecto

**Asignatura:** Desarrollo Orientado por Objetos (DOPO-POOB)

**Proyecto:** Proyecto Inicial - SlotMachine

**Entrega:** Ciclo 4 - Refactoring y Extensión

**Periodo:** 2026-2

## Requisitos de entrega

Según la guía del ciclo 4, la entrega contempla:

1. Diseño completo en Astah.
2. Implementación siguiendo los estándares de codificación y documentación de Java.
3. Casos de prueba unitarios en `SlotMachineC4Test`.
4. Mínimo dos casos de prueba compartidos en `SlotMachineCC4Test`.
5. Dos pruebas de aceptación preparadas para la presentación.
6. Documento de retrospectiva que incluya este ciclo y los anteriores.

Los productos deben publicarse en un repositorio Git. Además, en Moodle debe entregarse un archivo `.txt` con la URL del repositorio, cuyo nombre debe seguir la convención indicada en la guía.
