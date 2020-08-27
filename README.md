# Curso Definito de HTML y CSS

### Responsive desing: mostly fluid

Asi es como deberiamos implementar el mostly fluid en nuestros proyectos.

index.html
```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Mostly Fluid</title>
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="tablet.css" media="screen and (min-width:600px)">
	<link rel="stylesheet" href="desktop.css" media="screen and (min-width:800px)">
</head>
<body>
	<main class="container">
		<div class="c1"></div>
		<div class="c2"></div>
		<div class="c3"></div>
		<div class="c4"></div>
		<div class="c5"></div>
	</main>
</body>
</html>
```

tablet.css
```CSS
.c2, .c3, .c4{
	width: 50%;
}
```

desktop.css
```css
.container {
	width: 800px;
	margin-left: auto;
	margin-right: auto;
}

.c1{
	width: 60%;
}

.c2 {
	width: 40%;
}

.c3, .c4{
	width: 33%;
}

.c5{
	width: 34%;
}
```