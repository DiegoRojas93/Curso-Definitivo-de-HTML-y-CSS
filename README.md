# Curso Definito de HTML y CSS

### Etiqueta video

La etiqueta **video**, tiene algunos atributos como:

1. **controls:** agrega al video los controles necesarios para reproducir, pausar y adelantar.

2. **preload = auto:** hace que el navegador descargue el video, en el momento en el que se acceda a la página.

Hay otro atributo que indica al video que empice a reproducirse despues de haberse cargado la pagina. no es puena practica y puede ser penalizada ***hay que tn}ener cuidado en usarla.***

La etiqueta **source**, se puede colocar dentro de una etiqueta **video** varias veces, para especificar diferentes rutas. Esto para asegurar que cualquier navegador pueda mostrar el video.

**nota:** podemos especificar un rango de tiempo para que en cierto minuto del video empize a visualizarse y en otro se pueda finalizar.

esto se hace como una extencion en la ruta del **src** tan solo es agregar el sigiente codigo, los numeros son la cantidad de segundos.

`#t=10,60`

```HTML
<source src="./Episodio4.m4v#t=10,60" />
```