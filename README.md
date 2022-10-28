# fundamentals

(20222Q) 81.75 - Fundamentos del desarrollo de software y análisis de datos en Python

Integrantes: Ignacio Robles y Tomas Silberman

TP Integrador: Crimes in Boston

Hipotesis previa: 

1. Año a año los incidentes fueron aumentando.

Hipotesis rechazada. Aumentaron desde 2015 a 2017, pero en 2018 se vió una gran disminución.

2. Los fines de semana hay menos incidentes.

Hipotesis comprobada. Hay un equilibrio diario, siendo que los sabados y domingos son los dias con menores incidentes.

3. Los tiroteos se dan en su mayoría a la madrugada

Hipotesis rechazada. Los tiroteos se dan en su mayoría en las horas laborales, con picos durante la tarde, aunque el distrito A1 es la excepción.

4. Hay barrios mas peligrosos que otros

Hipotesis comprobada. Cerca del 70% de los incidentes se concentran en 3 distritos.

5. La mayoria de los incidentes son de Part Three (menor gravedad) y la minoría de Part One (mayor gravedad).

Hipotesis comprobada. En la gran mayoría de los barrios, esta es la situación predominante.

Descripción:

Los hechos de inseguridad e incidentes en Boston (USA) se repiten día a día y son demasiado frecuentes. En tan solo 4 años se registraron creca de 320.000 casos de este tipo. Teniendo esto en cuenta, decidimos tomar este dataset con el objetivo de realizar algún tipo de análisis acerca de los hechos para luego poder sacar conclusiones, realizar recomendaciones o entender en cierto punto, que es lo que está sucediendo en la ciudad.

El dataset cuenta con todos los incidentes que tuvo la ciudad de Boston a lo largo de cuatro años (2015,2016,2017,2018). Este incluye los tipos y grupos de incidentes, como por ejemplo hurtos, disputas verbales, robos de autos o accidentes de tránsito. Además, se especifican detalles como si hubo disparos en el incidente, la fecha, hora y la ubicación.

Para empezar, lo que hicimos fue limpiar el dataset con la finalidad de tener los datos reales y realizar un análisis correcto. Eliminamos columnas innecesarias que no nos iban a servir para lo que nos queremos concentrar y buscamos comunicar y además de esto dropeamos los registros duplicados. Cabe destacar que los INCIDENT_NUMBER se encuentran de cierta manera ‘repetidos’ debido a que un incidente puede contar con distintos tipos de ofensa detallados. Para resolver esto, lo que hicimos fue quedarnos con un solo INCIDENT_NUMBER en nuestro análisis creando un nuevo dataset.

A medida que fuimos ejecutando el código fuimos escribiendo algunas explicaciones para entender qué es lo que estábamos intentando expresar. Igualmente, en esta sección va a quedar mucho más clara y concisa la idea de lo que queremos concluir.

Una conclusión que podemos sacar es que los incidentes se dan mayormente en verano (junio, julio y agosto), que es cuando las personas tienen una mayor frecuencia de salir a la calle. Dejando a febrero cómo el mes en el cual menos incidentes se reportaron. Sumado a esto, los días con menor cantidad de incidentes son los domingos que interpretamos es cuando las personas suelen quedarse en su casa y hay menos movimiento.

Los incidentes se generan en su mayoría en una franja horaria, que es cuando la gente sale de trabajar. Los problemas se agudizan entre las 16hs y 19hs. Reforzando la seguridad y tratando de mejorar la fluidez del tránsito en ese horario creemos que mejoraría mucho la cantidad de incidentes.

Con respecto a los distritos, B2 resulta ser el que más incidentes tuvo a lo largo de estos años, por lo tanto es el distrito que podría necesitar la mayor cantidad de seguridad y móviles policiales. También, es el distrito con mayor cantidad de incidentes con disparos, por lo tanto la policía de Boston tiene que poner un ojo en ese barrio. 

Sumado a lo anterior, pudimos descubrir un principio de Pareto con respecto a los disparos. Llegamos a la conclusión que reforzando la seguridad en B2, B3 Y C11 se progresaría demasiado en cuanto a este tema, esto debido a que entre estos tres barrios se dividen el 72% de los ‘shootings’.

También quedaron registradas las calles con mayor número de incidentes, quedando marcadas así como las de mayor peligro.

Por otro lado, realizamos un análisis con un boxplot que nos dió que la mayor cantidad de tiroteos se encuentran en un rango desde las 6hs hasta las 21hs, algo razonable ya que es el horario en el cual la gente se encuentra en la calle transitando la ciudad. Igualmente, hay algunas excepciones por barrio, por ejemplo en el distrito A1 suelen haber mayores tiroteos en la madrugada. Lo que concluimos con esto es que no conviene transitar ese barrio de noche y es una zona que la policía debe tener en la mira.

Para terminar con este trabajo, ubicamos los incidentes en un mapa dejando en claro que la mayor cantidad de ellos se encuentran distribuidos por todo el centro de la ciudad. Aquí se concluye que hay una menor cantidad en las afueras y suburbios de la ciudad.