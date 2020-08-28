# Curso Definito de HTML y CSS

### Formularios: Select

Podemos usar la etiqueta **datalist** y a etiqueta **option** para permitir que el usuario selecione una lista de opciones que pueda elejir.

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Select</title>
</head>
<body>
	<main>

		<input list="cursos"> <!--Permite visualizar el item de lista-->

		<datalist id="cursos"> <!--nombre de la lista-->

			<option value="JavaScript">lenguaje</option> <!-- value muestra la opcion a escoger y su contenido mustra el detalle de esta opción-->

			<option value="HTML:5">no es lenguaje</option>
			<option value="CSS3">no es lenguaje</option>
			<option value="Web Standars"></option>
		</datalist>

	</main>
</body>
</html>
```
Esta es la mejor practica, debido a que al usuario puede buscar su item sin hacer scroll (muy util para mobile first) y ademas captura el dato que el usuario ingrese si no esta la opcion que este predetermina por el navegador