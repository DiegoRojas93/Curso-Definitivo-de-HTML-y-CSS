# Curso Definito de HTML y CSS

### Formularios: Input type submit vs. Button tag

Dememos usar el **Input type submit** para poder enviar los datos de un formulario (este input debe estar como hijo dentro de  la etiquete form).

Debemos usar la etiqueta **Button** para otas cosas, el cual podemos personalizarlo seleccionando el tipo de boton por medio del su atripbuto ***Type***

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<body>
	<input type="submit">

	<button>Enviar</button>

	<br>
	<br>
	<br>

	<input type="submit" value="Enviar">

	<button type="submit">Enviar datos</button>
</body>
</html>
```

**Nota:** *submit* significa enviar, si elegimos submit en un input o boton significa esta dos etiquetas enviaran datos.