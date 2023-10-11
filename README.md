# Resumen
En este proyecto vamos a utilizar análisis factorial y métodos de agrupamiento para encontrar patrones comunes en los municipios de la región de La Araucanía y Los Ríos.

# Introducción

Durante las últimas décadas las actividades humanas han modificado extensivamente la superficie de la tierra produciendo en muchos casos una degradación de los sistemas ecológicos de la tierra. Uno de los cambios más importantes ha sido el aumento de los bosques plantados, los datos de la evaluación global de los recursos forestales (FAO, 2020) indican que los bosques plantados alcanzan el 3.12% del bosque total a nivel mundial. Este aumento no se distribuye equitativamente en el mundo, encontrándose en Suramérica el mayor incremento a nivel mundial, dónde el 99% de este aumento corresponde a plantaciones forestales de especies exóticas (FAO, 2020). Chile, es uno de los países que muestra un mayor incremento en superficie de plantaciones forestales de Eucalyptus spp. and Pinus spp. a nivel global (FAO, 2020). Esto a partir de la implementación y consolidación de un modelo exportador y bonificaciones entregas para fomentar esta actividad entre los años 1974 y 2012 (Heilmayer et al., 2020, Niklitschek, 2007). De esta manera, la industria forestal se transformó en una de las principales actividades económicas ubicandose como la segunda más importante del país después de la minería, con una contribución estimada al PIB de un 3% del PIB, y fomentando el desarrollo de la industria de la celulosa, y la exportación de productos forestales.

Los efectos que produce la expansion de las plantaciones forestales sobre el territorio han generado controversia debido a sus potenciales impactos. Algunos de estos impactos son la disminución en la disponibilidad de agua (Lara et al., 2009) y el aumento del riesgo de incendios forestales (Carrasco et al., 2021, Gomez-Gonzalez et al., 2018). Los efectos positivos que se le atribuyen a esta actividad están relacionados a la posible disminución de la presión sobre los bosques naturales (Pirard et al., 2016), la protección del suelo contra la erosión (Cimini et al., 2016), y la contribución al crecimiento económico (Alfonso & Miller, 2021)

Debido a la magnitud del incremento de las plantaciones forestales, y a los posibles efectos sobre el territorio tanto negativos como positivos, la academia como distintos colectivos han pedido mejorar la planificación de esta actividad (Peña-cortés et al., 2021, Heilmayer et al., 2022). En este sentido, dentro de la fase de diagnóstico de la elaboración de planes de ordenamiento territorial es necesario identificar los principales factores de localización relacionados con la expansion de las plantaciones forestales, esto permite una comprensión más profunda del sistema y permite generar  modelos de simulación con el objetivo de apoyar los procesos de toma de decisiones por parte de los distintos actores.  


# Metodos

En este proyecto vamos a utilizar técnicas de reducción de la dimensionalidad (Análisis factorial) y agrupamiento para identificar patrones en los municipios de la regiones de La Araucania y Los Ríos en relación a los patrones espaciales que se observan en las teselas de plantaciones forestales a nivel clase.

# Patrones espaciales

# Anáilisis Factorial 

# Agrupamiento 

 Las técnicas de agrupamiento son parte de un grupo de técnicas de aprendizaje no supervisado que se caracterizan por trabajar con datos no etiquetados (cita). El agrupamiento de los datos permite identificar grupos con observaciones que presentan características comunes, identificables e interpretables, ayudando a reducir la complejidad de la información original. Esto permite generar un entendimiento más profundo de los datos. Esta técnica es comúnmente utilizada en una gran variedad de diciplinas, y es una herramienta fundamental dentro de la aplicación del marco de trabajo de toma de decisiones basadas en datos (cita).

 Actualmente existe una gran variedad de algoritmos de agrupamiento, por ejemplo, podemos elegir entre doce algoritmos en la librería SKLEARN de Python. Dentro de estos algoritmos se pueden distinguir tres grandes grupos: los algoritmos basados en prototipos, algoritmos jerárquicos, y algoritmos basados en la densidad. 
 
* Estos algoritmos se construyen a partir de definir un prototipo que define el grupo. Entre ellos encontramos el k-means, k-medoids, Afinity propagation

* Los algoritmos jerárquicos buscan identificar grupos de forma sucesiva y en forma jerárquica grupos y subgrupos que se pueden representar siguiendo una estructura de árbol. Esto permite identificar como se modifica la pertenencia de una observación a un grupo, en distintas escalas, la selección final del número de grupos óptimos queda a criterio del analista en este caso y a métricas de validación de cluster como Silhoutte.

* Los algoritmos basados en la densidad pueden tener cualquier forma quedando los grupos definidos a partir de su densidad. El patrón queda determinado por dos parámetros que deben ser introducidos, la cantidad de puntos mínimos para especificar un patrón, y la cercanía que deben tener los puntos para ser considerados parte de un agrupamiento.
  
# Resultados 

# Discusión
