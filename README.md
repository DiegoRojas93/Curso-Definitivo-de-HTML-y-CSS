# Curso Definito de HTML y CSS

### CSS: Pseudo clases y pseudo elementos

**[Pseudoclases:](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes "Pseudoclases:")** Definen el estilo de un estado especial de un elemento.


**[Pseudoelementos:](https://developer.mozilla.org/es/docs/Web/CSS/Pseudoelementos "Pseudoelementos:")** Define el estilo de *una parte* especifica de un elemento.

```CSS
.main-nav{
	margin-top: 10px;
	list-style: none;
	padding-left: 0;
	background-color: #13a4a4;
}

.main-nav__item {
	display: inline-block;
}

.main-nav__item a {
	color: white;
	padding: 5px;
	border-radius: 2px;
	text-decoration: none;
}

/* pseudoClases */

.main-nav__item a:hover {
	color: blue;
}

.main-nav__item a:active {
	color: red;
}

/* pseudoElemento */

.main-nav__item a::after{ /* Despues del elemento agregale este contenido*/

	content: " | ";
}

```
