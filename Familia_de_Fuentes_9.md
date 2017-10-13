Familia de Fuentes

La familia de la fuente se indica con la propiedad font-family
La font family debería tener varias fuentes, por si el browser no soporta alguna
La primera fuente tiene que ser la que uno quiere, la última una genérica
Si el nombre de la font-family tiene más de una palabra se escribe entre comillas. Ej: "Times New Roman"
Más de una font-family se especifica separados por coma​
​
​
https://developer.mozilla.org/en-US/docs/Web/CSS/font-family
​
​

​
​
​Contenedores y CSS
Fuentes - Tamaño
La propiedad font-size setea el tamaño de la fuente.
Puede ser, absoluto o relativo.
​
​
Fuentes - Tamaño Absoluto
Ajusta el texto con un tamaño específico.
No se puede cambiar el tamaño de letra en todos los navegadores.
Es útil cuando se sabe dónde se va a mostrar.

Posibles Valores
xx-small
x-small
small
Medium
Large
x-large
xx-large
​
​
​
Fuentes - Tamaño Relativo
Ajusta un tamaño relativo alrededor de los elementos.
Permite al usuario cambiar la letra de los browsers.
Si no se especifica el tamaño de la fuente, es por defecto 16px.
​
Posibles Valores
larger
smaller
Fuentes - Tamaño


Otra opción es usar valores numéricos:
Pixeles (px): Es absoluto, indica al browser los pixeles que tiene que medir la fuente. No es accessible
Em (em): Es relativo al parent. Por default 1 em = 16 px , 2em = 32px.
Rem (rem): Es relativo al root (body).
Porcentaje: Es relativo, un porcentaje del tamaño del elemento padre.
​
​
​
​
​
​
https://developer.mozilla.org/en-US/docs/Web/CSS/font-size


Fuentes - Tamaño Relativo
Ejemplo: Cada DIV usa fuente del doble de su contenedor.


<h1>Título suelto</h1>
<p>Un párrafo de texto.</p>
<div>
<h1>Título div</h1>
<div>
<h1>Título div div</h1>
<p>Un párrafo de texto.</p>
</div>
</div>
div {
font-size: 2em;
}
