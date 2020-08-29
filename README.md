# Curso Definito de HTML y CSS

### Flexbox-layout

Display flex es una propiedad para tener layout mas dinamicas.

Display flex nos permite tener mas carasteristicas bajo la manga:

1. **aling-items:** esta propiedad indica como se van a acomodar de forma vertical el contenido del contennedor padre. Debe ser aplicado en el contenedor padre y debe tener una altura muchoi mayor que la altura de uno de sus items.

sus valores son:

- ***flex-start***:posiciona los items en la parte superior del contendedor padre
- ***flex-end***:posiciona los items en la parte inferior del contendedor padre
- ***center***: centra los items del contendedor padre
- ***stretch***: la altura de los item dependera de la altura del contenedor padre; los hijos no podran tener una altura definida para que funcione.
- ***baseline***: la altura de los items dependera del contenido del mismo. los items no podran tener una altura definida para que funcione.

2. **order:** podemos jugar con el posicionamiento en el que se ordenan los items. Por regla general si en algunos items no se le proporcionen un orden, ellos se posicionaran primero y luego se posicionaran a aquellos que se les aya dado un orden especifico.

No importa si se le haya dado un item un orden de 1, primero se posicionaran los que no tienen order y su orden dependera de como hallan sido ordenasdos en el HTML. Esta propiedad va a ir en item.

3. **flex-grow:** Esta propiedad va a ir en item. Y lo que proporcionara al item, es que su ancho crecera lo suficienta para que el widht del container padre sea ocupado totalmente.

4. **[Flex-basis](https://developer.mozilla.org/es/docs/Web/CSS/flex-basis "Flex-basis")** debera poner un valor relativo (rem) y debera estar en todos los item hijos.Los item no deberan tener un widht y deberan tambien tener un *flex-grow* para que funcione.

Lo que pasara es que el item bajara si no tiene espacio sificiente en el contenerdor padre. Cada item que baje tendra un ancho suficientemente largo para que ocupe todo el widht del contenedor.