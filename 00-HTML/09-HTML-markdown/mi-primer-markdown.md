<!-- Esto rd un comentario al igual que con la extension .html -->
<!--Un archivo markdown sirve para tomar apuntes o hacer documentacion rápida-->

# Esto es como un h1 en .html
## Esto es como un h2 en .html
### Esto es como un h3 en .htmml ....etc

<!-- Para texto -->
## Texto en negrita
Asi se escribe un parrafo normal
Ase se escribe en **negrita** o asi tmb __negrita__ o pulsando en ctrl+b sobre la palabara.
## Texto en cursiva
Así en *cursiva* y asi en _cursiva_ o pulsando esobre la palabra y ctrl+i

<!-- Lineas de separación -->
## Para lineas de separación
***
---
___

<!-- Listas -->
## Lista:
* Manzana
* Agua
* Guacamole

## Lista ordenada
1. Manzana
2. agua
3. aguacate

<!-- Links -->
## Links
[Ir a goolge](https://google.com)

## Imágenes
[Ir a foto](../animales/patos.jpg)
<!-- Para ver la foto le ponemos un asterisco delante -->
![Ver foto](../animales/patos.jpg)

<!--Blockquote-->
## Blockquote
> Esto es un Blockquote

<!-- Para escribir codigo en linea, como haciamos con <code> en la extensión .html usamos `` ...estas comillas se llaman backtics -->
## Uso de backtics (``) para escribr codigo
Ejemplo: con la etiqueta `<u></u>` escribimos en negrita en .html

<!-- Para escribir un BLOQUE de codigo usamos tres ```, y si ademas añadimos el lenguaje que es al lado (```html) lo identifica -->
## Para bloques de codigo
```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="/00-HTML/05-HTML_media/assets/yo_2.jpg">
    <title>Etiquetas extra</title>
  </head>

```
---

```javascript
function sumar(a, b){
  return a+b
}
```

<!-- Por último, en un archivo markdown puedes usar cualquier etiqueta de html -->

Esto es un <mark>marcado</mark> con etiqueta html