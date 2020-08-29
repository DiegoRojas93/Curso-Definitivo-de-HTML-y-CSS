# Curso Definito de HTML y CSS

### Variables (custom properties)

La pseudo-clase **[:root](https://developer.mozilla.org/es/docs/Web/CSS/:root ":root")** de CSS selecciona el elemento raíz de un árbol que representa el documento. En HTML, :root representa el elemento <html> y es idéntico al selector html, excepto que su especificidad es mayor.

:root puede ser útil para declarar variables CSS globales:

```CSS
:root {
  --main-color: hotpink;
  --pane-padding: 5px 42px;
}
```

***Ejemplo:***

```CSS
:root{
	--primary-color: #003476;
	--secondary-color: #b4d2f7;
	--header-size: 4rem;
	--font: 1.8rem;
}

* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

html {
	font-size: 62.5%
}

header {
	width: 100vw;
	height: 15vh;
	background-color: var(--primary-color);
}

main {
	width: 100vw;
	height: 70vh;
	font-size: var(--font);
}

h1 {
	font-size: var(--header-size);
	color: var(--primary-color);
}

footer {
	width: 100vw;
	height: 15vh;
	background-color: var(--secondary-color);
}
```