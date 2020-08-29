# Curso Definito de HTML y CSS

### Max/Min width y Max/Min height

Para jugar con el Max y Min widht, debemos siempre deberemos tener **width** base en *pocentaje* y el **Max/Min width** en *pixeles*

```css
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

main {
	width: 100vw;
	height: 100vh;
	background-color: rgb(128, 128, 247);
}

section {
	width: 80%;					/*width base: que siempre este en porcentaje*/
	min-width: 320px;		/*ancho minimo alcanzable: siempre en px*/
	max-width: 500px;		/*ancho maximo alcanzable: siempre en px*/
	height: 500px;
	margin: 0 auto;
	background-color: lavender;
}
```

si un contenido es mayor que su contenedor (ej: un text sobresalga de un contenedor) podemos implementar **min-height** para que cuando el conetido sobresalga  el contenedor creasca ala par de su contenido.

Tambien podemos limitar el maximo que podra soportar el contenedor  **max-height**

```css
section {
	width: 80%;
	min-width: 320px;
	max-width: 500px;
	min-height: 500px;  /*su altura minima es de 500px pero podra expandirse a medida del tamaño de su contenido*/
	margin: 0 auto;
	background-color: lavender;
}
```