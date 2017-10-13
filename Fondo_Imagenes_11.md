###Fondo - Imágenes

Se puede usar una imagen de fondo.
La propiedad es background-image
Por defecto la imagen se repite para cubrir todo el fondo.

body {
background-image:url(imagen.jpg);
}

Cuando se usa una imagen de fondo, hay que tratar de que no interfiera con el texto.
Para que la imagen no se repita, hay que usar la propiedad background-repeat.
​
body {
background-image:url(imagen.jpg);
background-repeat:no-repeat;
}
​
[Referencia](https://developer.mozilla.org/en-US/docs/Web/CSS/background-repeat "Referencia")
