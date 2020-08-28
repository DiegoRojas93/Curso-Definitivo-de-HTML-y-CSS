# Curso Definito de HTML y CSS

### rem

Un REM siempre va a referenciar al tamaño de fuente de la etiqueta HTML.

```CSS
html {
	font-size: 62.5%;
}

p {
	font-size: 1.6rem; /*1.6rem = 16px; 1rem = 10px*/
}
```

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>REM</title>
</head>
<body>
	<main>
		<p>Soy un parrafo</p>
		<div>
			<p>Soy un parrafo anidado</p>
			<div>
				<p>Soy un parrafo anidado</p>
				<div>
					<p>Soy un parrafo anidado</p>
					<div>
						<p>Soy un parrafo anidado</p>
					</div>
				</div>
			</div>
		</div>
	</main>
</body>
</html>
```