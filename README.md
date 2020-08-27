# Curso Definito de HTML y CSS

### Responsive design: Imágenes responsive

Esta es la mejor tecnica para trabajar imagenes responsive.


Index.html
```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<main>
		<picture>
			<source media="(min-width:1300px)" srcset="./images/large.jpg">
			<source media="(min-width:1000px)" srcset="./images/medium.jpg">
			<img src="./images/small.jpg" alt="Es una imagen de ejemplo" />
		</picture>
	</main>
</body>
</html>
```

./style.css
```CSS
img {
	width: 100%;  /*Es tu mejor amigo*/
}
```

**Nota:** Recuerda siempre poner la etiqueta source con mayor min-width por encima de la etiqueta source con menor min-width.

Todas las etiquetas source y img deben estar dentro de la etiqueta picture.

El width de las imagenes siempre estaran al 100%.