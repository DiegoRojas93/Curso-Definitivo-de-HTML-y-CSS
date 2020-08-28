# Curso Definito de HTML y CSS

### Especificidad en los selectores

¿como se controla el orden al declarar css?

hay tres maneras de declarar la especificidad de css

- **importancia:** La importancia es uno de los conceptops más... pues... importantes.

si dos declaraciones tienen la misma importancia, la especificidad de las reglas decidirá cuál se debe aplicar. Si las reglas tienen la misma especificidad, el orden de las fuentes controla el resultado final.

los estilos se aplicaran segun su impotancia

1. La hoja de estilo de agente de usuario (el naegador aplicara sus estilos a ciertas etiquetas)

2. Declaraciones normales en hojas de estilo de autor (Nuestros.css)

3. Declaraciones importantes en las hojas de estilos ( utilizan el ***!important***)

- **Especificidad:** los selectores de que implementamos en los archivos css tentran su rango de importancia; aqui enumeraremos su orden de importancia de mator a menor.

1. !important

2. inline style (los estylos que se aplican en la etiqueta style del archivo .HTML ó en las etiquetas hijas del body)

3. #id

4. .class

5. etiquetas (etiquetas de html llamadas en el archivo .css)

- **Orden de las fuentes**: En nuestros estilos, las declaraciones al final del documento anularan a las que sucedan antes en caso de un conflicto.

**Nota:** *cascade* es el algoritmo de css que toma para aplicar los estilos.