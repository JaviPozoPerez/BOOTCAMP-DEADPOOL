# Módulo de CSS

## Recursos

* [Fuentes de Google](https://fonts.google.com/)
* [Paletas de colores](https://coolors.co/)
* [Colores oficiales de marcas](https://brandcolors.net/)
* [Fondos vectoriales](https://www.svgbackgrounds.com/)
* [Gradientes Predefinidos](https://uigradients.com/)
* [Generador de Gradientes](https://cssgradient.io/)
* [Generador de fuentes fluidas](https://www.fluid-type-scale.com/) 
* [Generador de Clip paths para recortar fotos con formas](https://bennettfeely.com/clippy/)

* [Nombres propios de colores CSS](https://www.w3schools.com/colors/colors_names.asp)

### Iconos

* [Iconos de Bootstrap](https://icons.getbootstrap.com/)
* [Iconos de Font Awesome](https://fontawesome.com/)


## Juegos CSS

* [CSS dinner (Para selectores CSS)](https://flukeout.github.io/)
* [Selectores CSS](https://css-speedrun.netlify.app/)

* [Batallas CSS](https://cssbattle.dev/)

* [FLEXBOX FROGGY](https://flexboxfroggy.com/#es)
* [Flexbox Zombies](https://mastery.games/flexboxzombies/)



## ¡TATUAJES! de trozos de código importantes.

### Para centrar un elemento en pantalla.

```css
div { 
  margin-inline: auto;
}
``` 

### Usualmente el contenido rpincipal de la web tiene unos estilos parecidos a los siguientes:

```css
main {
  width: 80%;
  max-width: 1100px;
  margin-inline: auto;
}
``` 

### Para centrar una caja `absolute` dentro de otra.

```css
.caja {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  /* recordad que el transform: translate toma los tantos por ciento de SI MISMOS, no de su padre */
}
```

### Para centrar completamente una o varias cajas dentro de otra

```css
.caja-padre {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

## Teorías

* [Propiedades CSS Heredables](https://web.dev/i18n/es/learn/css/inheritance/)
* [CSS Flexbox - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)