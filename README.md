Buscar V
========
## Definición

<p align="justify">
La función <i>BUSCAR V</i> nos permite buscar un <i>valor</i> dentro de una <i>tabla</i> y saber si dicho valor existe o no. De <i>IZQUIERDA</i> a <i>DERECHA</i>
</p>

#### Ejemplos uso:

<p align="justify">
Esta función es útil en caso de trabajar en el sector del comercio o las ventas al por menor. Por ejemplo es posible buscar el nombre de un artículo y obtener, como resultado, el número de dicho artículo o su precio.
</p>

<p align="justify">
Por ejemplo, supongamos que eres un profesor con una lista de alumnos elaborada en Excel. Podrías hacer uso de <i>BUSCARV</i> para introducir el nombre de un estudiante y obtener, de manera instantánea, su calificación desde una celda correspondiente.
</p>

## Estructura

```
= BUSCARV(	Valor que desea buscar, 
		rango en el que quiere buscar el valor, 
		el número de columna en el rango que contiene el valor devuelto, 
		Coincidencia exacta o Coincidencia aproximada indicado como 0/FALSO o 1/VERDADERO
	  )
```

## Desarrollo

Tenemos la siguiente tabla:

<p align="center">
	<img src="https://github.com/ginppian/Excel-BuscarV/blob/master/imgs/img2.png" width="465" height="324">
</p>

* Problema:

<p align="justify">
Teniendo el <i>IDENTIFICADOR o NÚMERO DE PIEZA</i> 	del producto queremos saber cuál es su precio.
</p>

<p align="center">
	<img src="https://github.com/ginppian/Excel-BuscarV/blob/master/imgs/img3.png" width="1086" height="350">
</p>

<p align="justify">
Tomamos una celda C1 donde escribiremos X <i>IDENTIFICADOR</i>.
Tomamos otra celda adjunta C2, y escribimos nuestra función <i>BUSCARV</i>.
Como primer parámetro le pasaremos la ubicación de la C1 o la primera celda donde meteremos X valor.
Como segundo parámetro le pasaremos un <i>RANGO</i> de donde queremos <i>BUSCAR</i> de <i>IZQUIERDA</i> a <i>DERECHA</i> </i>ARRIBA</i> <i>ABAJO</i>
</p>
## Fuente

<p>
<a href="https://support.office.com/es-es/article/Funci%C3%B3n-BUSCARV-0bbc8083-26fe-4963-8ab8-93a18ad188a1">Función BUSCARV</a>
</p>