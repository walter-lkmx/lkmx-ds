---
title: Tokens básicos
date: 2020-01-02
slug: tokens-basicos
---

## Espaciado

El espaciado es una forma de unificar paddings, márgenes y alturas.

Las variaciones de espaciado están definidas por una escala de números divisibles entre cuatro:

|nombre   |medida   |
|---------|---------|
|zero     |0px      |
|xxxs     |4px      |
|xxs      |8px      |
|xs       |12px     |
|s        |16px     |
|m        |24px     |
|l        |32px     |
|xl       |40px     |
|xxl      |64px     |
|xxxl     |80px     |


## Tipografía

Nuestro sistema tipográfico es el núcleo de nuestra interfaz. Ayuda a transmitir la jerarquía del contenido de nuestra página y tiene la capacidad de traducirse a una multitud de idiomas.

Roboto es el tipo de letra estándar de LKMX para Web, iOS y Android. Nuestros pesos de fuente se seleccionan para centrarse en la accesibilidad.

**Familia tipográfica**

|'Roboto', 'Helvetica Neue', 'Helvetica', Arial, sans-serif   |
|-------------------------------------------------------------|

**Font Weight**
- Light - 300
- Regular - 400
- **Medium - 500**
- **Bold- 700**

**Jerarquía**

| Tipo | Propiedades |
|--|--|
| Data Viz 1 | Font size: 56px<br>Line height: 68px<br>Font weight: 300 / Light<br>Color: Black Pepper 400  |
| Data Viz 2 | Font size: 34px<br>Line height: 40px<br>Font weight: 300 / Light<br>Color: Black Pepper 400  |
| H1 | Font size: 28px<br>Line height: 36px<br>Font weight: 500 / Medium<br>Color: Black Pepper 400  |
| H2 | Font size: 24px<br>Line height: 32px<br>Font weight: 700 / Bold<br>Color: Black Pepper 400  |
| H3 | Font size: 20px<br>Line height: 28px<br>Font weight: 700 / Bold<br>Color: Black Pepper 400  |
| H4 | Font size: 16px<br>Line height: 24px<br>Font weight: 700 / Bold<br>Color: Black Pepper 400  |
| H5 | Font size: 16px<br>Line height: 24px<br>Font weight: 400 / Regular<br>Color: Black Pepper 400  |
| Body | Font size: 14px<br>Line height: 20px<br>Font weight: 400 / Regular<br>Color: Black Pepper 300  |
| Body 2 | Font size: 13px<br>Line height: 20px<br>Font weight: 400 / Regular<br>Color: Black Pepper 300  |
| Small | Font size: 12px<br>Line height: 16px<br>Font weight: 400 / Regular<br>Color: Black Pepper 300  |


**Variaciones**

Son modificadores en la jerarquía de las fuentes tipográficas. Es posible combinarlos.

| Tipo | Propiedades / Uso |
|--|--|
| Label | Font weight: 500 / Medium<br>Para etiquetas de campo (Body 1/2 y Small) |
| Button | Font weight: 500 / Medium<br>Para botones, encabezados, sub-encabezados y énfasis en textos de párrafo |
| **CAPS** | Font weight: 700 / Bold; Mayúsculas<br>Para botones en Android y textos capitalizados  |
| Hint | Color: Gris<br>Para texto de ayuda y/o contenido secundario  |
| <span style="color: #ff004f">Error</span> | Color: LKMX Red<br>Para textos de error (usualmente en tamaño pequeño)  |
| <span style="color: #00d2ff">Link</span> | Color: LKMX Blue; decoración textual: delineado (sólo al darle hover)<br>Para hipervínculos (sin importar el tamaño de fuente) |
| Mono | Familia: 'Roboto Mono', 'Courier New' Courier, monospace<br>Para contenido monoespacial (código, preformateado, etc.)  |
| <span style="background-color: #060444; padding: 0 5px; color: white;">Inverse</span> | Color: LKMX Dark<br>Para cualquier texto que necesite ser resaltado con un color de fondo. Procurar usar texto color blanco.  |


## Profundidad

Nuestros niveles de profundidad unifican sombras paralelas y sombras internas. Ayudan a crear áreas de interés visual y capas en nuestro producto.

Cada nivel de profundidad debe seleccionarse en función del contenido, el fondo y los otros niveles de profundidad utilizados en la página. Use las sugerencias a continuación como referencia para saber cuándo usar cada una.

-- CUADRADO --

**Profundidad -1** <br>
Usado para contenedores inset

-- CUADRADO --

**Profundidad 1** <br>
Profundidad de tarjeta estándar

-- CUADRADO --

**Profundidad 2** <br>
En hover, la profundidad aumenta

-- CUADRADO --

**Profundidad 3** <br>
En notificaciones activas, asíncronas y pop-ups

-- CUADRADO --

**Profundidad 4** <br>
En tarjetas sobre fondos blancos, así como en menús y ventanas de aviso


## Movimiento

Esta guía está escrita para diseñadores que desean ofrecer un movimiento consistente en sus prototipos, y para desarrolladores que desean una guía de valores de referencia rápida.

**Propósito**

Todas las animaciones de la interfaz de usuario deben tener un propósito conocido. Esta intención podría ser resolver un problema de diseño o comunicar la personalidad de nuestra marca. Más adelante, se explicará cómo identificar en detalle el propósito de una animación.

**Evitar crear obstáculos**

La animación no debe interponerse en el camino del usuario para completar su tarea. Una animación nunca aumentaría intencionalmente la dificultad de una tarea, pero puede ser fácil dejarse llevar mientras se diseña algo visualmente agradable. Evite florecer extra y cantidades de tiempo innecesarias. En cambio, mantenga las animaciones simples, rápidas y directas.

Los estados de carga y recuperación son una excepción; Hay momentos en los que no se puede evitar la espera.

**Entregar deleite**

Como se mencionó anteriormente, cuando no se puedan evitar los tiempos de espera, úselo como una oportunidad para expresar la identidad de nuestra marca y al mismo tiempo deleitar al usuario en momentos de frustración. La diversión es uno de nuestros valores fundamentales, después de todo.

**Mantenerlo flexible**

Las buenas animaciones de interfaz deben ser flexibles y siempre deben responder a la entrada del usuario, incluso mientras la animación se mueve. Piensa en ello como una conversación. Si un usuario comienza a darse cuenta de que se omite o ignora su entrada, se pierde la confianza y la calidad de su experiencia comienza a degradarse. La animación sin bloqueo genera confianza al responder siempre a la entrada del usuario, sin importar en qué parte de la animación se encuentre actualmente. El tiempo de la animación también puede variar según el tamaño de la transición de la interfaz de usuario (que se está llevando a cabo, aunque generalmente se clasifican con un rango de 200 ms a 500 ms).

**Centrarse en la interacción**

Aunque las animaciones deben ser rápidas, es importante tener en cuenta la mentalidad basada en tareas de su usuario al decidir sobre múltiples factores de animación. Para continuar con la metáfora de la conversación, las animaciones siempre deben sentirse bien para interactuar. Juzgue esto probando la animación por usted mismo en contexto, así como obteniendo opiniones externas. Esto recae en que las animaciones son flexibles, incluso si el tiempo está fuera del rango recomendado, pero se siente bien.

**Tener en cuenta el rendimiento**

Las animaciones que tardan en interactuar en la web impactan negativamente en la experiencia. El bajo rendimiento puede anular incluso la experiencia más pensada. Las animaciones deberían usar las propiedades más eficientes. Las compensaciones se pueden usar para aligerar la carga cognitiva de muchos objetos que animan, al tiempo que mejoran el rendimiento percibido del usuario.
