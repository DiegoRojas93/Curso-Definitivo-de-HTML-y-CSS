# Curso Definito de HTML y CSS

### Formulario de calentadio

Hay dos formas de crear un formulario typo calendario donde se pueda pedir la hora, el dia, la semana, el mes y el año, para que el usuario pueda ingresar estos datos y lo podamos usar

```HTML
<!DOCTYPE html>
<html lang="es">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Document</title>
	</head>
	<body>
		<!DOCTYPE html>
	<html lang="es">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Calendario</title>
	</head>
	<body>

		<!-- Esta el la forma de hacer un formulario tipo calendario, la cual es la forma más larga de hacer-->

		<form action="">
			<label for="hora">
				<span>Hora</span>
				<input type="time" id="hora" name="hora">
			</label>
			<label for="dia">
				<span>Dia</span>
				<input type="date" id="dia" name="dia">
			</label>
			<label for="semana">
				<span>Hora</span>
				<input type="week" id="semana" name="semana">
			</label>
			<label for="mes">
				<span>Mes</span>
				<input type="month" id="mes" name="mes">
			</label>

			<input type="submit" value="enviar">
		</form>

	<!-- Otra opcion de hacer un calendario, seria de la forma más corta -->

		<form action="">

			<label for="calentadio">
				<span>calendario</span>
				<input type="datetime-local" id="calentadio" name="calendario">
			</label>

			<input type="submit" value="enviar">
		</form>

	</body>
</html>
```

El atributo **name** permite hacer la referencia del nombre que le asignamos al *id* del input y del *for* del label con el valor del dato que ingresa el usuario.

`mes = dato que el usuario halla asignado`

Esto hace permisible el envio de datos a la base de datos de la página.