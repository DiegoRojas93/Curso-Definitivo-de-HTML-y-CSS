# Curso Definito de HTML y CSS

### Display:flex

Display flex es una propiedad para tener layout mas dinamicas.

Display flex nos permite tener mas carasteristicas bajo la manga:

1. **flex-diraction:** esta propiedad indica como se van a acomodar los hijos. Debe ser aplicado en el contenedor padre.
sus valores son:

- ***row***: es por default y muestra una fila de los items hijos
- ***column***: muestra una columna de los items hijos
- ***row-reverse***: muestra una fila de los items hijos pero estos estan al contrario.
- ***column-reverse***: muestra una columna de los items hijos pero estos estan al contrario.

2. **flex-wrap:** esta propiedad indica como se van a acomodar los hijos si estos no ven mas espacio en su contenedor, es decir que los items hijos caeran uno bajo el otro si no encuentran el espacio suficinete para que esten en su forma de horizontal. Debe ser aplicado en el contenedor padre y sus valores son:

- ***nowrap:*** no se envolveran.
- ***wrap:*** se envolveran (caeran uno bajo el otro).
- ***wrap-reverse:*** se envolveran (caeran uno encima del otro).

3. **justify-content:** alinea el contenido (los items hijos) de forma horizontal, sus valores son: center, space-between, space-around, space-evenly(el espacio es el mismo) flex-end,flex-start etc.