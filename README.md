# Guía de Ejercicios Físicos

Este proyecto tiene como objetivo la creación de una guía estructurada de ejercicios físicos mediante el uso del sistema de control de versiones Git. Cada tipo de ejercicio se desarrolla en una rama independiente, donde se documenta progresivamente a través de commits bien estructurados. Al finalizar, todas las ramas se fusionan en la rama principal, consolidando así la guía completa.

## Objetivos

- Aplicar el uso de Git en un proyecto colaborativo.
- Desarrollar habilidades en la gestión de ramas y resolución de conflictos.
- Practicar el uso de commits siguiendo el estándar de conventional commits.
- Documentar información técnica de manera clara y progresiva.

## Estructura del Proyecto

```
GuiaDeEjercicios/
├── ejercicios/
│   ├── cardio.md
│   ├── fuerza.md
│   ├── flexibilidad.md
│   ├── entrenamiento_funcional.md
│   ├── yoga.md
│   ├── pilates.md
│   ├── ciclismo.md
│   ├── natacion.md
│   ├── boxeo.md
│   └── crossfit.md
└── README.md
```

Cada archivo dentro de la carpeta `ejercicios/` contiene la información correspondiente a un tipo de ejercicio. Estos archivos se desarrollaron en ramas individuales, utilizando al menos cinco commits por archivo.

## Tipos de Ejercicio Documentados

- [Ejercicio Cardio](ejercicios/cardio.md)
- [Ejercicio de Fuerza](ejercicios/fuerza.md)
- [Ejercicio de Flexibilidad](ejercicios/flexibilidad.md)
- [Entrenamiento Funcional](ejercicios/entrenamiento_funcional.md)
- [Yoga](ejercicios/yoga.md)
- [Pilates](ejercicios/pilates.md)
- [Ciclismo](ejercicios/ciclismo.md)
- [Natación](ejercicios/natacion.md)
- [Boxeo](ejercicios/boxeo.md)
- [CrossFit](ejercicios/crossfit.md)

## Metodología de Trabajo

1. Crear la carpeta principal del proyecto (`GuiaDeEjercicios`) y la subcarpeta `ejercicios/`.
2. Crear una rama por cada tipo de ejercicio.
3. En cada rama:
   - Crear un archivo `.md` correspondiente.
   - Realizar al menos cinco commits utilizando el formato de conventional commits:
     - Agregar el título del ejercicio.
     - Añadir la descripción.
     - Incluir beneficios.
     - Instrucciones para realizar el ejercicio.
     - Consejos y precauciones.
4. Fusionar todas las ramas en la rama principal (`main`).
5. Resolver manualmente cualquier conflicto que surja durante las fusiones.
6. Subir la rama principal y las demás ramas al repositorio remoto.

## Resultados Esperados

Al finalizar el codigo, la rama principal debe contener todos los archivos de ejercicios completamente integrados, cada uno con su respectiva documentación estructurada. Esta guía puede servir como referencia para rutinas físicas organizadas por tipo de entrenamiento.
