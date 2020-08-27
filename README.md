# Curso Definito de HTML y CSS

### Responsive desing:Layout shifter

Layout shifter es cambiar tu layout completamente para diferentes pantallas, lo que hace que en cada pantalla parezca un proyecto totalmente diferente.

index.html
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Layout shifter</title>
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="tablet.css" media="screen and (min-width:600px)">
	<link rel="stylesheet" href="tablet.css" media="">
	<link rel="stylesheet" href="desktop.css">
</head>
<body>
	<main class="container">
		<div class="c1"></div>
		<div class="c4">
			<div class="c2"></div>
			<div class="c3"></div>
		</div>
		<div class="c5"></div>
	</main>
</body>
</html>
```

tablet.css
```CSS
.c1 {
	width: 25%;
}
.c4{
	width: 75%;
}
.c5{
	width: 100%;
}
```

desktop.css
```css
.container {
	width: 800px;
	margin-right: auto;
	margin-left: auto;

	margin: 0 auto;
}

.c1 {
	width: 50%;
	order: 1;
}
.c4{
	width: 100%;
}
.c5{
	width: 50%;
	order: 2;
}
```