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


## Guías Tipográficas

Nuestro sistema tipográfico es el núcleo de nuestra interfaz. Ayuda a transmitir la jerarquía del contenido de nuestra página y tiene la capacidad de traducirse a una multitud de idiomas.

Roboto es el tipo de letra estándar de LKMX para Web, iOS y Android. Nuestros pesos de fuente se seleccionan para centrarse en la accesibilidad.

### Familia tipográfica

|'Roboto', 'Helvetica Neue', 'Helvetica', Arial, sans-serif   |
|-------------------------------------------------------------|

### Font Weight
- Light - 300
- Regular - 400
- **Medium - 500**
- **Bold- 700**

### Jerarquía
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


### Variaciones

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

<div style="width: 100px; height: 100px; background-color: #fdfdfd; box-shadow: rgba(82, 97, 115, 0.09) 0px 0px 8px 0px inset;"></div> 

**Profundidad -1** <br>
Usado para contenedores inset

<div style="width: 100px; height: 100px; background-color: #fdfdfd; box-shadow: rgba(0, 0, 0, 0.08) 0px 2px 4px 0px;"></div> 

**Profundidad 1** <br>
Profundidad de tarjeta estándar

<div style="width: 100px; height: 100px; background-color: #fdfdfd; box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 8px 0px;"></div> 

**Profundidad 2** <br>
En hover, la profundidad aumenta

<div style="width: 100px; height: 100px; background-color: #fdfdfd; box-shadow: rgba(0, 0, 0, 0.12) 0px 8px 16px 0px;"></div> 

**Profundidad 3** <br>
En notificaciones activas, asíncronas y pop-ups

<div style="width: 100px; height: 100px; background-color: #fdfdfd; border: 1px solid rgb(218, 226, 230); box-shadow: rgba(0, 0, 0, 0.12) 0px 8px 16px 0px;"></div>

**Profundidad 4** <br>
En tarjetas sobre fondos blancos, así como en menús y ventanas de aviso
