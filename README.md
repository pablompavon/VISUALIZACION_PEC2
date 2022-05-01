<div style="width: 100%; clear: both;">
<div style="float: left; width: 50%;">
<img src="http://www.uoc.edu/portal/_resources/common/imatges/marca_UOC/UOC_Masterbrand.jpg", align="left">
</div>
<div style="float: right; width: 50%;">
<p style="margin: 0; padding-top: 22px; text-align:right;">M2.859 · Visualización de datos · PEC2</p>
<p style="margin: 0; text-align:right;">2021-2 · Máster universitario en Ciencia de datos (Data science)</p>
<p style="margin: 0; text-align:right; padding-button: 100px;">Estudios de Informática, Multimedia y Telecomunicación</p>
</div>
</div>
<div style="width:100%;">&nbsp;</div>


# Visualización PEC 2

<div class="alert alert-block alert-info">
<strong>Nombre y apellidos: Pablo Martínez Pavón</strong>
</div>

## Visualización 1

### Nombre: 
Pie Chart - Gráfico circular

### Origen: 
El gráfico circular más antiguo conocido generalmente se atribuye al Breviario estadístico de William Playfair de 1801, en el que se utilizan dos gráficos de este tipo. Este invento no fue muy utilizado al principio. Posteriormente Florence Nightingale lo adaptó para hacerlo más legible al reconfigurar el gráfico circular haciendo que la longitud de las cuñas fuera variable en lugar de su ancho. Esto fomentó su amplio uso, aún hoy.

### Descripción y funcionamiento: 
Es un gráfico estadístico circular, que se divide en porciones para ilustrar una proporción numérica. En un gráfico de este tipo, la longitud del arco de cada sector (y, en consecuencia, su ángulo central y su área) es proporcional a la cantidad que representa. 

### Ejemplos:
1. Playfair presentó una ilustración que contenía una serie de gráficos circulares. Uno de esos gráficos representaba las proporciones del Imperio Turco ubicado en Asia, Europa y África antes de 1789.

![imagen](https://user-images.githubusercontent.com/77053851/163562277-ed4fd727-e8db-4631-a936-285daeebbddf.png)

2. El ingeniero francés Charles Joseph Minard también usó gráficos circulares en 1858. Un mapa suyo de 1858 usó gráficos circulares para representar el ganado enviado desde toda Francia para el consumo en París.

![imagen](https://user-images.githubusercontent.com/77053851/163562337-c27fe23d-89e1-4253-b6d7-924cca6cbf1b.png)

### Tipo de datos y estructura: 
Sirve para mostrar el número de ocurrencias de cada nivel de una variable, por lo tanto se trata de una variable categórica. Los datos deberían tener forma de una tabla de frecuencias absolutas o relativas.

### Limitaciones: 
La principal limitación a la hora de usarla es el número de clases y su porcentaje, si hay muchas clases no se distinguirán todas correctamente; o si hay alguna muy pequeña esta en muchos casos no se verá correctamente. __Su uso está profundamente desaconsejado en las webs especialistas, aconsejando el uso de otras alternativas como los gráficos de barras__.

### Fuente:
1. [Wikipedia](https://en.wikipedia.org/wiki/Pie_chart)
2. [Data to Viz](https://www.data-to-viz.com/caveat/pie.html)

## Visualización 2

### Nombre:
Alluvial Diagram - Diagrama aluvial

### Origen:
Según las fuentes consultadas, son una subcategoría de los diagramas de Sankey. Los diagramas de Sankey llevan el nombre del capitán irlandés Matthew Henry Phineas Riall Sankey, quien utilizó este tipo de diagrama en 1898 en una figura clásica que mostraba la eficiencia energética de una máquina de vapor.
Con el tiempo, se ha convertido en un modelo estándar utilizado en ciencia e ingeniería para representar el balance de calor, los flujos de energía, los flujos de materiales y, desde la década de 1990, este modelo visual se ha utilizado en la evaluación del ciclo de vida de los productos.

### Descripción y funcionamiento:
Son un tipo de diagrama de flujo desarrollado originalmente para representar cambios en la estructura de una red a lo largo del tiempo. En alusión tanto a su apariencia visual como a su énfasis en el flujo, los diagramas aluviales llevan el nombre de abanicos aluviales que se forman naturalmente por el suelo depositado por las corrientes de agua. Sirven para analizar una evolución o hacer un seguimiento de un flujo desde su origen a su final.
En un diagrama aluvial, las variables se asignan a ejes verticales que son paralelos y los valores se representan con bloques en cada eje. La altura de un bloque representa el tamaño del grupo y la altura de un campo de flujo representa el tamaño de los componentes contenidos en ambos bloques conectados por el campo de flujo.

### Ejemplos:
1. Diagrama de Sankey original.

![imagen](https://user-images.githubusercontent.com/77053851/163563412-ee5f3ac7-9b87-4fb8-b620-376e16b92d7e.png)

2. Uno de los diagramas de Sankey más famosos es el Mapa de la campaña rusa de Napoleón de 1812 de Charles Minard. Es un mapa de flujo que superpone un diagrama de Sankey a un mapa geográfico. Fue creado en 1869, anterior al primer diagrama de Sankey de Sankey de 1898.

![imagen](https://user-images.githubusercontent.com/77053851/163563492-8f5ec842-6246-4089-9146-842e3588d19e.png)

3. Un ejemplo de un diagrama aluvial que ilustra cómo el estudio científico de la neurociencia se fusionó con otras disciplinas relacionadas para formar su propio campo.

![imagen](https://user-images.githubusercontent.com/77053851/163563520-18102f96-2ab9-48bf-870c-622dccf24e5d.png)

### Tipo de datos y estructura:
Necesitamos variables cuantitativas y adscritas a estas o el número de ocurrencias de los niveles o una variable numérica de la que se puedan realizar operaciones para cada uno de los grupos que se analicen. También sería válida una evolución cronológica de un conjunto de variables.

La estructura en la que se presentarían este tipo de datos son una tabla.

### Limitaciones:
La posición de los nodos es muy importante: existen algoritmos para minimizar el número de cruces entre enlaces.
El desorden excesivo hace que la figura sea ilegible. Se recomienda descartar las conexiones débiles.

### Fuente:
1. [Wikipedia](https://en.wikipedia.org/wiki/Alluvial_diagram)
2. [Data to Viz](https://www.data-to-viz.com/graph/sankey.html)
3. [Data Viz Project](https://datavizproject.com/data-type/alluvial-diagram/)

## Visualización 3

### Nombre:
Raincloud plot - Gráfico de nubes de lluvia

### Origen:
Se trata de una combinación de gráficos que existían previamente, por lo tanto su origen no está claro. El paper principal es muy reciente, del año 2019 y revisado en 2021, y se cita en las fuentes empleadas; aunque en él se citan ejemplos anteriores que siguen un planteamiento similar como: Ellison 1993, Hintze 1998, Wilson 2018, etc.

Nace de la necesidad de disponer de visualizaciones que transmitan de manera precisa y transparente los aspectos clave de los efectos estadísticos y los datos sin procesar con una distorsión mínima. Los enfoques anteriores, como trazar diagramas de barras de mediana o media condicional junto con barras de error, han sido criticados por distorsionar el tamaño del efecto, ocultar patrones subyacentes en los datos sin procesar y oscurecer los supuestos en los que se basan las pruebas estadísticas más utilizadas. Esto es un enfoque de visualización de datos que supera estos problemas, brindando la máxima información estadística y preservando la naturaleza deseada de "inferencia de un vistazo" de los diagramas de barras y otros dispositivos de visualización similares. 

### Descripción y funcionamiento:
Estos gráficos permiten  visualizar datos sin procesar, densidad de probabilidad y estadísticas de resumen clave, como la mediana, la media y los intervalos de confianza relevantes en un formato atractivo y flexible con redundancia mínima. De una manera sencilla, se observa la curva de distribución y complementariamente se ve la distribución real de los puntos. Se emplea jittering, que es el acto de agregar ruido aleatorio a los datos para evitar el overplotting en gráficos estadísticos, para lograr una visión clara de los datos. Además puede acompañarse de un boxplot.

### Ejemplos:

1. Pueden revelar información que incluso un diagrama de caja más datos sin procesar podría ocultar, como una distribución bimodal que puede no ser fácilmente "observada" desde los puntos de datos sin procesar.

![imagen](https://user-images.githubusercontent.com/77053851/163671381-7e924264-11b1-49c5-96e6-13037b603004.png)

2. Diagrama que muestra datos sin procesar, densidad, diagramas de caja y media con un IC del 95 % para la interacción ubicación/duración para el puesto de investigación. [Fuente](https://www.researchgate.net/figure/Raincloud-plot-showing-raw-data-density-boxplots-and-mean-with-95-CI-for-the_fig3_331403264)

![imagen](https://user-images.githubusercontent.com/77053851/163671900-d7717fb2-5091-4545-810c-e169a09a54dc.png)

### Tipo de datos y estructura:
En principio, este gráfico está pensado para datos cuantitativos (numéricos continuos), sin embargo como ocurre para otras técnicas se puede apoyar en datos cuantitativos para demostrar el comportamiento estadístico de una variable cuantitativa diferenciando para cada nivel de una variable cuantitativa.

En este caso, la estructura de interés sería un vector con los datos numéricos pertenecientes a una variable o una tabla que tenga una variable numérica y otra cualitativa con diferentes niveles.

### Limitaciones:
Se observa en el segundo ejemplo que cuando hay mucho overplotting, si no se limita el jittering la visualización podría ser confusa.
Esto es el principal motivo para evitar usar esta técnica con datos categóricos.

### Fuente:
1. [Paper](https://wellcomeopenresearch.org/articles/4-63)
2. [CedricScherer](https://www.cedricscherer.com/2021/06/06/visualizing-distributions-with-raincloud-plots-and-how-to-create-them-with-ggplot2/)
3. [TDS](https://towardsdatascience.com/making-it-rain-with-raincloud-plots-496c39a2756f)   
