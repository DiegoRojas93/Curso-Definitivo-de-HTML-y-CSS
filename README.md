# Curso Definito de HTML y CSS

### combinadores: Child combinator y Descendant combinator

[![Combinadores](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2864%29-d9e9849d-5ced-4933-b653-eb9e6113f124.jpg "Combinadores")](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2864%29-d9e9849d-5ced-4933-b653-eb9e6113f124.jpg "Combinadores")

El **[combinador hijo](https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator "combinador hijo")** (>) se coloca entre dos selectores CSS. Solo coincide con los elementos que coinciden con el segundo selector que son hijos directos de los elementos que coinciden con el primero.

Es decir, que si tenemos estos se selectores `h2 > p` con esta propiedad `color: red;`, su traduccion seria *aplicale a los parrafos el color rojo solo si son hermanos generales despues de haber encontrado la etiquetahis directos de la etiqueta `div`*

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Combinadores</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div>

		<article>
			<p>Soy un parrafo</p>
		</article>
		<article>
			<p>Soy un parrafo</p>
		</article>

		<section>
			<div>
				<H2>Soy un titulo</H2>
				<p>soy un parrafo</p>  <!--Se aplicaran sus estilos-->
			</div>
		</section>

		<p>Soy un parrafo</p>  <!--Se aplicaran sus estilos-->
	</div>
</body>
</html>
```

```CSS
div > p { /*si la etiqueta p es hija directa de una eqtiqueta div aplicale los sigiente estilos*/

	color: red;

}
```

El **[combinador descendiente](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator "combinador descendiente")** , normalmente representado por un solo carácter de espacio ( ), combina dos selectores de modo que los elementos que coinciden con el segundo selector se seleccionan si tienen un elemento ancestro (padre, padre padre, padre padre, etc.) que coincida con el primer selector. Los selectores que utilizan un combinador descendiente se denominan selectores descendientes.

Es decir, que si tenemos estos se selectores seguidos entre si, por ejemplo:`h2 p` que tenga esta propiedad `color: red;`, su traduccion seria *aplicale a los parrafos el color rojo solo si estan con tenidos dentro de la etiqueta `div`*

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Combinadores</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div>

		<article>
			<p>Soy un parrafo</p>
		</article>
		<article>
			<p>Soy un parrafo</p>
		</article>

		<section>
			<div>
				<H2>Soy un titulo</H2>
				<p>soy un parrafo</p>  <!--Se aplicaran sus estilos-->
			</div>
		</section>

		<p>Soy un parrafo</p>  <!--Se aplicaran sus estilos-->
	</div>
</body>
</html>
```

```CSS
div p { /*si la etiqueta p esta adentro de una etiqueta div aplicale los sigiente estilos*/

	color: red;

}
```