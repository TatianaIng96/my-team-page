# Make It Real - MY TEAM PAGE

This is a solution to the my team page project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

# Make It Real - My Team Page

<img src="./assets/desktop-preview.jpg" width="700">

## Reto

Su desafío es construir una pagina responsive para mostrar a tu team y lograr que se parezca lo más posible al diseño.

Puedes usar cualquier herramienta que te guste para ayudarte a completar el desafío. Entonces, si tienes algo que te gustaría practicar, no dudes en intentarlo.

Sus usuarios deberían poder:

- Ver el diseño óptimo según el tamaño de pantalla de su dispositivo

## Diseño

Los diseños están en formato JPG estático. El uso de archivos JPG significará que deberá usar su mejor criterio para estilos como "tamaño de fuente", "padding" y "margen".

### Style Guide

Los diseños se crearon con los siguientes anchos:

- Mobile: 375px
- Desktop: 1440px

## Colores

### Primary

- Black: #000000

## Tipografía

### Body Copy

- Font size: 18px/14px

### Font

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 500


### Screenshot
![](./assets/captura-mobile%20(3).jpeg)
![](./assets/captura-mobile%20(1).jpeg)

.


## Mi proceso

### Lo construi con:

- Semantica HTML5
- Propiedades de estilos sass
- CSS propiedades
- Flexbox 
- Diseño responsive

### What I learned

Aprendí a utilizar los estilos sass con html ademas de agregar el resposive con @media querys y tambien con grids

```css
  @media screen and (min-width: 600px) {
    .wrapper {
        max-width: 1440px;
    }
  }
```

```css
  .flex-header {
    display: grid;
    grid-template-columns: repeat(
        auto-fit,
        minmax(345px, 1fr)
    );
    gap: 30px;
  }
```

tambien aprendí a utilizar la etiqueta figure la cual permite manipular la imagen que envuelve

```html
  <figure id="profile-2">
      <div class="flex">
          <img src="/assets/photo_2.png">
          <div class="role">Art Director</div>
      </div>
      <figcaption>Saba Cabrera</figcaption>
  </figure>
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

### Continuar desarrollando

Me gustaria enfocare bien en aprender el diseño responvive, este aún no me queda muy claro, apesar que que hago busquedas y las aplico a mi codigo y fuciona, a mi no me queda muy claro como hacerlo ahorrando código

### recursos

- [resource 1](https://developer.mozilla.org/es/docs/Web/HTML/Element/figcaption) - este recurso fue muy importante porque aprendí a manipular una figura de todos los moos posibles, ademas de agregarles titulos debajo y arriba, vertical y horizontalmente.


## Author

Leidy Tatiana Cardona

Yo me inspire en un proyecto encontrado en la web escrito por Hibiki Taguchi

