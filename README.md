# Curso Definito de HTML y CSS

### Responsive desing: medias queries

Responsive desing es una buena practica para que nuestra paginas se eslaen y se vean bien para cualquier dispositivo.para usarlo debemos saber que es una **media querie** y un ***Break point.***

Nuestros proyectos deben ser pensados primero en **Mobile First** ó **Mobile Only** y la mejor practica de trabajarlo es hacer un archivo .css que referencie los estilos para cada uno de los tamaños que necesitemos; y linkearlos a nuestro HTML en el orden de mobile a desktop.

```HTML
<Link href="style.css" rel="stylesheet"> <!--Tus estilos para enforcados a mobile firts-->

<Link href="tablet.css" rel="stylesheet" media="screen and (min-width: 768px)"> <!--Tus estilos para enforcados a tammanis minimos de 768-->
```