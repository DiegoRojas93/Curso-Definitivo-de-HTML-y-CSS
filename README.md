# Curso Definito de HTML y CSS

### Responsive design: Column Drop

Column Drop es un tipo layout que permite reacomodar sus contendido a posiciones de columna (mobile firts) a filas (desktop) cada vez que pase a de mobile a desktop.

index.html
```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Column drop</title>
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="tablet.css" media="screen and (min-width:600px)">
	<link rel="stylesheet" href="tablet.css" media="">
	<link rel="stylesheet" href="desktop.css">
</head>
<body>
	<main class="container">
		<div class="c1"></div>
		<div class="c2"></div>
		<div class="c3"></div>
		<div class="c5"></div>
		<div class="c6"></div>
	</main>
</body>
</html>
```

style.css
```CSS
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

html {
	font-size: 62.5%;
}

.container {
	display: flex;
	flex-wrap: wrap;
}

.c1, .c2, .c3, .c4, .c5{
	width: 100%;
	min-width: 150px;
	height: 150px;
}

.c4 {
	height: auto;
}
.c1 {
	background-color: #003475;
}
.c2 {
	background-color: #0062d2;
}
.c3 {
	background-color: #b4c2f7;
}
.c4 {
	background-color: #d5dfef;
}
.c5 {
	background-color: #dfe1e5;
}
```

tablet.css
```CSS
.c1{
	width: 25%;
	order: 1;
}

.c2{
	width: 75%;
	order: 2;
}

.c3{
	width: 100%;
	order: 3;
}

.c4{
	width: 100%;
	order: 4;
}

.c5{
	width: 100%;
	order: 5;
}
```

desktop.css
```css
.c1{
	width: 30%;
}

.c2{
	width: 40%;
}

.c3{
	width: 30%;
}

.c4{
	width: 50%;
}

.c5{
	width: 50%;
}
```