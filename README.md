# Curso Definito de HTML y CSS

### em

EM = es un acronimo de elemento y lo que hace es tomar el tamaño de fuente que tenga el padre directo ejemplo:

```CSS
.container {
  font-size: 20px
}

.containerdiv {
  font-size: 2em
}
```
aqui los el tamaño del div que esta dentro de la clase container tenda un tamaño de 40px, ya que

`1em = 20px`

y como estamos asignandole 2 em seria como 20px + 20px

y si por ejemplo tenemos el siguiente caso :

```CSS
.container {
  font-size: 20px
}

.containerdiv {
  font-size: 2em
}

.containerdivp {
  font-size: 1.5em
}
```

a continuacion veremos que la etiqueta p tendra un tamaño de fuente de 60px.

Ya que toma como referencia el tamaño de su padre ( 40px ) y haria la siguiente operacion 40*1.5 que es igual a 60, es por eso que la etiqueta p tomo el valor de 60px