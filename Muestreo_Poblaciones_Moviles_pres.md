<style>
.footer {
color: black;
background: #E8E8E8;
position: fixed;
top: 90%;
text-align:center;
width:100%;
}
.midcenter {
position: fixed;
top: 50%;
left: 50%;
}
.small-code pre code {
font-size: 1em;
}
.reveal h3 {
word-wrap: normal;
-moz-hyphens: none;
}
.reveal h1 {
word-wrap: normal;
-moz-hyphens: none;
}

.blue .reveal .state-background {
background: #E8E8E8;
}
.blue .reveal h1,
.blue .reveal h2,
.blue .reveal p {
color: steel blue;
}

.exclaim .reveal .state-background {
  background: black;
} 

.exclaim .reveal h1,
.exclaim .reveal h2,
.exclaim .reveal p {
  color: white;
}

</style>

Muestreo en Poblaciones Móviles: Caso específico en centros comerciales
========================================================
author: Felipe Jiménez
date: noviembre 23, 2014
autosize: true
transition: rotate
transition-speed: slow

**"Essentially, all models are wrong, but some are useful"**    
George E. P. Box    

Contenido
====================
type:prompt
transition: rotate

- Introducción:conceptos
- Supuestos básicos de muestreo en centros comerciales
- Locaciones 
- Horarios
- Ejemplo de selección
- Frecuencia de visita

Introducción
====================
type:alert
transition: rotate
incremental: true

> **Objetivo:** 
- Introducirnos en el muestreo riguroso de poblaciones móviles (humanas) con el fin de disminuir sesgos.
- Se explora el artículo "*Improving the Quality of shopping Center Sampling*" de Seymour Sudman en el que se indica que un procedimiento de muestreo riguroso en centros comerciales.   

> **Conceptos:**
- Población móvil

Ventajas
====================
type:prompt
transition: rotate
incremental: true

- bajo costo.
- no existen desplazamientos grandes de los entrevistadores
- se pueden investigar en diferentes dimensiones sensoriales

==========================================================
title:false
type: blue
id: slide1
<div style="font-weight:bold; color:steel blue;position: fixed; top:60%; text-align:center;left:70%;padding:1em;font-size:140%">SUPUESTOS</div>

Supuestos básicos de muestreo en centros comerciales
========================================================
transition: fade

- El artículo basa sus supuestos en muestras que sean generalizables para la población de todo un país o toda una región.

- **Todos los habitantes de este país o región deben tener probabilidad igual y mayor que cero de ser encontrados en el centro comercial**

- Distancia, ideología, gusto son algunos de los factores que harán imposible el cumplimiento de este factor.

- El sesgo variará en función del tópico de la encuesta, pero el autor recomienda **no realizar** estos estudios cuando se midan ingresos por ejemplo.


Selección de la muestra 
========================================================
transition: rotate

- Inicialmente se debe seguir el procedimiento clásico: **PPT en cada centro comercial.**
- se utiliza usualmente el volumen total de ventas por centro comercial.
- En caso de la negativa de la administración para realizar el estudio **se puede sustituir** con un mall similar en características( tamaño y ubicación).
- Si la muestra es para un país o región, **se debería incluír más de un mall** para poder calcular la variancia ( cada mall es un cluster).

========================================================
title:false
type: blue
id: slide2
<div style="font-weight:bold; color:steel blue;position: fixed; top:60%; text-align:center;left:70%;padding:1em;font-size:140%">LOCACIONES</div>

Muestreo en entradas del centro comercial
========================================================
transition: rotate

- **Todas las entradas deben tener posibilidad de ser seleccionadas** para la muestra.Se mencionan dos procedimientos:

* **Las entradas pueden ser seleccionadas con la misma probabilidad**.Este procedimiento puede ser ineficiente ya que se debe gastar tiempo en entradas con poca afluencia.

* **Se puede muestrear las entradas con probabilidad proporcial al tamaño al número de clientes que ingresan**.Este dato se puede obtener de conteos anteriores.De esta forma, muestrear clientes en cada entrada será inversamente proporcional a la medida de su tamaño.

Muestreo dentro del centro comercial
========================================================
transition: fade

- **Es menos recomendado** por las dificultades de selección con respecto a la selección en entradas.
- Idealmente las locaciones deben ser seleccionadas con **probabilidad proporcional al tráfico**.
- Se deben establecer **reglas para establecer los límites de las zonas** y la escogencia de personas en caso de "empates", para que la selección no sea ambigua.

==========================================================
title:false
type: blue
id: slide3
<div style="font-weight:bold; color:steel blue;position: fixed; top:60%; text-align:center;left:70%;padding:1em;font-size:140%">HORARIOS</div>


Selección de los horarios a muestrear
========================================================
transition: fade
left: 55

- Características de lo visitantes varían en función de la hora del día,día de la semana o del mes, temporada y factores como clima u otros eventos.

> **Pasos:** 

1. Escoger **la periodicidad** de cada segmento temporal.
2. Decidir entre escoger intervalos **con igual probabilidad( más ineficiente) o con PPT según la afluencia de público(más costoso)**.Si se decide por el segundo, los conteos deben ser robustos(más de una semana)

***

> **Consejos:** 

- Los horarios deben de tratarse con la misma seriedad que las locaciones y muestrearse similarmente.
- Escoger la periodicidad en función del tiempo medio que toma realizar la entrevista.
- No excluír arbitrariamente periodos.


====================
type:prompt
transition: rotate
incremental: true
title:false

> **Ejemplo de selección:**     


<img src="Muestreo_Poblaciones_Moviles_pres-figure/Ejemplo Selección-1.png" title="plot of chunk Ejemplo Selección" alt="plot of chunk Ejemplo Selección" style="display: block; margin: auto;" />



Otras consideraciones en la selección
========================================================
transition: fade

- se supone que **solo el número y no las características de la población se ven afectadas por eventos especiales o el clima**.Sin este supuesto, se debería tomar un conteo de una cantidad de tiempo que pueda representar fielmente a la población objetivo.

- la entrevista y la selección de las personas debe realizarse por **al menos dos personas** para evitar eliminar la probabilidad de selección de algunas personas

==========================================================
title:false
type: blue
id: slide4
<div style="font-weight:bold; color:steel blue;position: fixed; top:60%; text-align:center;left:70%;padding:1em;font-size:140%">FRECUENCIA DE VISITA</div>


Escogencia del periodo de tiempo a preguntar
========================================================
transition: fade

- Se estima mediante la pregunta directa al entrevistado.**Se utiliza para ajustar las selecciones**.
- Se recomienda periodos no muy cortos(**2 semanas**) ni muy largos (**1 mes**) por el olvido o efecto telescopio.

> El supuesto es que no todos los informantes responderán de manera perfecta, pero que los errores se netean y no están relacionados con el tópico de la investigación.

- **Si la selección fue en el interior del mall, una pregunta adicional se debe realizar** para estimar el tiempo en el centro ( para ajustar por probabilidad de selección) ya que pueden existir diferencias en el tiempo consumido.

Procedimientos para pesar las personas seleccionadas
========================================================
transition: fade

-Inverso del número de visitas y el tiempo en el mall(para la selección en el interior),dandole más peso a los entrevistados con menor cantidad de visitas y menos tiempo.

> Este procedimiento puede reducir el sesgo si los supuestos no son violados fuertemente.


Alternativas y complementos al ajuste con pesos
========================================================
transition: fade

-**Submuestreo basado en el número de visitas:**este procedimiento es evitado porque complica la logística de campo.
-**Cuotas:**El autor señala que el uso de cuotas en conjunto con los pesos pueden disminuir de manera importante los sesgos:

**-->** sexo: mujeres>hombres en compras y visitación.    
**-->** Diferencias según condición de empleo y grupo de edad.    

> Luego de estos procedimientos(**Pesos+Cuotas**) el sesgo puede quedar en el orden del 10% respecto a muestras probabilísticas.

==========================================================
title:false
type: blue
id: slide5
<div style="font-weight:bold; color:steel blue;position: fixed; top:60%; text-align:center;left:70%;padding:1em;font-size:140%">CONCLUSIONES</div>

- Supuestos de difícil cumplimiento en la práctica.
- Controles para la selección(lugar, tiempo y frecuencia)
- Procedimientos para disminuir el sesgo( pesos, cuotas)   

> Si es tolerable el sesgo en beneficio del ahorro en tiempo y costos estos estudios son una aceptable alternativa,además de incluír la posibilidad de realizar diferentes pruebas sensoriales.
