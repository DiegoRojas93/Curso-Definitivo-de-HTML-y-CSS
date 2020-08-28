# Curso Definito de HTML y CSS

### combinadores: General Sibling

[![Combinadores](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2864%29-d9e9849d-5ced-4933-b653-eb9e6113f124.jpg "Combinadores")](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2864%29-d9e9849d-5ced-4933-b653-eb9e6113f124.jpg "Combinadores")

El [combinador hermano general](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_combinator "combinador hermano general") (~) separa dos selectores y hace coincidir todas las iteraciones del segundo elemento, que siguen al primer elemento (aunque no necesariamente de forma inmediata) y son hijos del mismo elemento padre .

Es decir, que si tenemos estos se selectores `h2 ~ p` con esta propiedad `color: red;`, su traduccion seria *aplicale a los parrafos el color rojo solo si son hermanos generales despues de haber encontrado la etiqueta `h2`*