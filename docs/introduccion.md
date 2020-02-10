---
title: Nombre del sistema de diseño
date: 2019-09-15 07:42:34
slug: introduccion
---

En el proceso de desarrollo de sistemas, se involucran muchas especificaciones e implementaciones diferentes de diseño, esto puede ocasionar dificultades tanto a diseñadores como a desarrolladores, y afectar la eficiencia de desarrollo. Este sistema pretende homogeneizar las especificaciones de la interfaces de usuario tanto para proyectos internos como externos y así reducir los costos innecesarios de diseño y su implementación en código.

Pensado para mejorar la experiencia del usuario y de todos los miembros del proyecto en desarrollo, ***[NOMBRE-DS]*** tiene como objetivo hacer del maquetado y prototipado una tarea sencilla y accesible para todos los involucrados en el uso del producto.

___

## Valores [SAFE]

Nuestros principios dan forma a la manera en que trabajamos día a día y nos ayudan a tomar decisiones de diseño complejas. Cada uno fue elegido para representar las facetas centrales de un gran diseño y un excelente software.

**Seguro**: Elimina cualquier ambigüedad. Permite a la persona ver, entender y actuar con confianza.

**Ágil**: Agiliza y optimiza el flujo de trabajo. Anticipa las necesidades de la persona para ayudarlo a trabajar mejor, de manera más inteligente y más rápida.

**Fácil**: Crea familiaridad y favorece la intuición de la persona al aplicar la misma solución al mismo problema.

**Estético**: Demuestra respeto por el tiempo y la atención de la persona a través de una experiencia bien pensada y atractiva visualmente.
___
## Composición

**Tokens**

Es la parte más pequeña del Sistema de Diseño. Su función primara es almacenar información del UI que permite construir recursos, componentes y patrones de forma sostenible y coherente.

- Un Token es un elemento inmutable que requiere un proceso de adopción y/o modificación bien definido y justificado.
- Un token es la materia prima o herramienta que utilizamos para obtener elementos más complejos, como recursos, componentes y patrones.


Ejemplos:
- Paletas de colores
- Tipografía
- Reglas de espaciado
- Reglas no visuales como guías de movimiento


**Recursos**

Unidades de UI más complejas, se usan de la misma forma que los componentes pero con funciones y propósitos fijos. Dependen de los tokens, pero se construyen de forma distinta.

Ejemplos:
- Iconografía
- Recursos de marca
- Ilustraciones

**Componentes**

Bloques de tokens agrupados con un comportamiento funcional específico que sirven para una variedad de aplicaciones. Son la parte más reconocible del Sistema de Diseño y están sujetos a más cambios y adecuaciones que otros elementos.

Estructura para organizar componentes:

├── Categoría  

├──── Tipo de componente

├──────── Variación


**Niveles de complejidad**

No todos los componentes son iguales, presentan características y niveles distintos de complejidad.

- **Nivel 1**: Componentes conformados solamente por Tokens.
- **Nivel 2**: Componentes construidos con componentes de **Nivel 1** además de Tokens adicionales y micro-interacciones simples.
- **Nivel 3**: Componentes construidos usando otros componentes además de lógica y métricas de interacción. Debido a su complejidad algunos de estos componentes son cubiertos mediante Patrones.

**Patrones**

Solución a un problema común de diseño, siempre vinculado a un caso de negocio. Provee un contexto específico sobre una solución, cómo se ajustó dicha solución y qué conjunto de componentes y tokens se utilizaron para llegar a ese resultado.

- Debe ser reusable y vinculado a componentes.
- Debe ser documentado y proveer guías sobre cómo es que el problema fue resuelto en el negocio.
