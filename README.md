# Curso Definito de HTML y CSS

### Etiqueta form e input

Esta es la estructura de basica de un formulario.

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<body>
	<form action=""> <!--Action sirve para enviar los datos del formulario a la url de una base de datos-->

		<label for="nombre">
			<span>¿Cual es tu nombre?</span>
			<input type="text" id="nombre" placeholder="pepito"/>
		</label>

		<label for="inicio-platzi">
			<span>¿Qué dia comenzaste en Platzi?</span>
			<input type="date" id="inicio-platzi"/>
		</label>

		<label for="horario">
			<span>¿En que horario estudias?</span>
			<input type="time" id="horario"/>
		</label>
	</form>
</body>
</html>
```

Esta es la lista de los [Tipos de Inputs.](https://www.w3schools.com/html/html_form_input_types.asp "Tipos de Inputs.")

**Nota:** ***for*** y ***id*** los los atributos de label e inpust que conectan bien a estas dos etiquetas.