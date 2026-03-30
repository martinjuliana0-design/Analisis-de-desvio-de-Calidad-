# Análisis de Desvío de Calidad — Cámara de Aire en Aceto Balsámico Reducción 


---
# Descripción del proyecto 
Este proyecto surge de mi experiencia real como Analista de Calidad en una industria de fraccionamiento de productos alimentarios. Durante la inspección de pallets listos para despacho, se detectó un defecto visual en botellas de aceto balsámico reducción 250ml: una cámara de aire visible en varias unidades.
Lo que parecía un problema estético resultó ser un problema de contenido neto con consecuencias legales, operativas y económicas directas. Una botella con cámara de aire tiene menos líquido del declarado en etiqueta, lo que la convierte en producto no conforme que no puede comercializarse.
El objetivo de este proyecto fue estructurar ese problema como un análisis de datos: medir el defecto, cuantificar su impacto y proponer soluciones basadas en evidencia.
* El defecto no era detectable durante el fraccionamiento. La alta viscosidad del aceto reducción hace que el aire incorporado durante el llenado migre lentamente hacia la superficie, haciéndose visible recién después de días de reposo del producto paletizado.


---
# Objetivos 
El análisis buscó responder cinco preguntas concretas.
La primera fue determinar cuántas botellas de la muestra presentaban cámara de aire por encima del límite permitido y cuál era la magnitud real del defecto en términos de volumen.
La segunda fue verificar si el contenido neto real de las botellas afectadas estaba por debajo del límite legal de tolerancia establecido para productos de 250ml.
La tercera fue proyectar cuántas unidades del pallet completo estaban potencialmente afectadas, extrapolando los resultados de la muestra al universo total.
La cuarta fue cuantificar el impacto económico del evento para la empresa, incluyendo el stock inmovilizado, la pérdida de insumos y el costo de la mano de obra de reproceso.
La quinta fue proponer acciones correctivas basadas en los datos para evitar que el problema se repita.


---
# Hipotesis 
Antes de analizar los datos, la hipótesis de trabajo fue la siguiente: el defecto de cámara de aire no era aleatorio ni puntual. Si el volumen promedio de aire incorporado en las botellas afectadas superaba significativamente el umbral máximo permitido de 12,5ml, entonces una proporción relevante del lote estaría sistemáticamente fuera de especificación, haciendo inviable la liberación del pallet sin intervención.
La hipótesis se confirmó. El promedio de cámara de aire en las botellas no conformes fue de 40,14 ml, más de tres veces el máximo permitido, y el 70% de la muestra estaba por debajo del límite legal de contenido neto.


---
# Metodología de análisis 
Se tomó una muestra representativa de 20 botellas del pallet afectado. Para cada botella se aplicó el método gravimétrico de verificación de contenido neto, que consistió en los siguientes pasos.
Primero se pesó el envase vacío para obtener la tara individual de cada botella de vidrio. Luego se pesó la botella con el producto para obtener el peso bruto. A partir de esos datos se calculó el peso neto del líquido restando la tara al peso bruto. Se midió directamente el volumen de la cámara de aire visible en cada botella. Finalmente se calculó el contenido neto real restando el volumen de cámara de aire al volumen nominal declarado de 250ml, y se comparó ese valor contra el límite legal mínimo de 237,5ml, que corresponde a una tolerancia del 5%.
La densidad del aceto reducción se tomó como valor de referencia de 1,20 g/ml. En el proceso real este dato era provisto por el laboratorio para cada lote fraccionado.
Las 20 botellas de la muestra representan una combinación de mediciones reales tomadas durante el evento y valores simulados para completar el tamaño muestral, declarados como tales en la documentación del archivo Excel.


---
# Kpis Analizados 
Los indicadores clave que guiaron el análisis fueron los siguientes.
* Porcentaje de botellas no conformes en muestra. El indicador principal del análisis. Mide qué proporción de las botellas inspeccionadas estaba por debajo del límite legal de contenido neto. El resultado fue 70%, lo que confirmó que el problema era sistemático y no puntual.
* Promedio de cámara de aire en botellas NC. Mide la magnitud del defecto en las botellas afectadas. El resultado fue 40,14 ml comparado contra el máximo permitido de 12,5 ml, es decir más de tres veces el umbral de tolerancia.
* Promedio de contenido neto real. Mide cuánto contenido tenían realmente las botellas de la muestra en promedio. El resultado fue 220,41 ml, es decir 29,59 ml por debajo del valor declarado en etiqueta.
* Botellas NC proyectadas al pallet completo. Extrapola el porcentaje de NC de la muestra al universo total de 1.356 botellas por pallet. El resultado fue 949 unidades potencialmente no conformes por pallet, sobre un total de 2.712 botellas inmovilizadas entre los dos pallets afectados.
* Días de cuarentena. Mide el tiempo durante el cual el stock estuvo inmovilizado sin poder comercializarse. El valor fue de aproximadamente 90 días, desde la detección del problema hasta la finalización del reproceso.
* Impacto económico total estimado. Consolida en un solo número el costo del evento para la empresa, sumando stock inmovilizado, pérdida de insumos y mano de obra de reproceso. El resultado fue $2.858.000 ARS estimados.


---
# Conclusiones 
El análisis permitió llegar a cuatro conclusiones concretas.
La primera es que el defecto no era visual ni aleatorio. Con un promedio de cámara de aire de 40 ml en las botellas afectadas y un máximo permitido de 12,5 ml, el problema triplicaba el umbral de tolerancia. Las botellas no conformes y las conformes eran dos poblaciones completamente distintas sin casos borderline, lo que indica una causa estructural en el proceso de llenado y no variaciones aleatorias.
La segunda es que el impacto operativo fue total, no proporcional. Aunque el 30% de las botellas del pallet estaba en condiciones de ser liberado, por protocolo de cuarentena ninguna unidad podía moverse hasta finalizar el reproceso completo. Esto significa que 407 botellas conformes estuvieron inmovilizadas durante 90 días sin ninguna razón técnica más que el protocolo. Logística lo registraba en un Excel de seguimiento y el sistema de semáforos en el depósito marcaba esos pallets como retenidos hasta resolución definitiva.
La tercera es que el problema no era caro de resolver sino caro de tener parado. El costo de la mano de obra de reproceso fue de $32.000 ARS, mientras que el stock inmovilizado representó $2.712.000 ARS, el 94,9% del impacto total. Esto demuestra que la urgencia no estaba en el costo de la intervención sino en el tiempo de inmovilización del producto sin poder generar ingresos.
La cuarta es que estructurar los datos convirtió una observación visual en un argumento de negocio. Sin el análisis, el evento quedaba registrado cualitativamente como "defecto detectado y reprocesado". Con el análisis, se puede demostrar exactamente qué pasó, cuánto costó y qué hacer para evitar que vuelva a ocurrir.


---
# Proyección a futuro 
Si el evento se repite sin implementar mejoras en el proceso, el impacto económico anual proyectado escala rápidamente. Con 2 eventos al año el costo proyectado es de $5.716.000 ARS. Con 4 eventos asciende a $11.432.000 ARS. Con 6 eventos alcanza los $17.148.000 ARS.
Frente a eso, implementar un control gravimétrico rutinario en la línea de fraccionamiento tiene un costo estimado de $150.000 ARS. El punto de equilibrio es de apenas 0,05 eventos evitados, es decir que con evitar menos de un evento la inversión ya está recuperada. A partir del primer evento evitado el ahorro neto es de $2.708.000 ARS. Esto convierte la mejora de proceso en una decisión de negocio rentable con retorno inmediato y medible, no solo en una buena práctica de calidad.
En cuanto a la evolución de la tasa de no conformidad, se estima que con la implementación de controles preventivos la tasa podría reducirse del 70% actual al 15% en el mediano plazo y al 5% en el largo plazo. Eso representaría una reducción de más de 880 botellas no conformes por pallet y un ahorro estimado de $2.500.000 ARS por lote procesado correctamente desde el inicio.


---
# Recomendaciones 
La primera recomendación es establecer un período de reposo obligatorio del pallet antes de la inspección final de calidad. Dado que el defecto solo se hace visible después de días de reposo por la alta viscosidad del producto, incorporar este tiempo en el flujo del proceso permitiría detectar el problema antes de que el pallet sea registrado como listo para despacho, reduciendo el impacto logístico y el tiempo de cuarentena.
La segunda recomendación es incorporar el control gravimétrico como método estándar de verificación de contenido neto en cada lote fraccionado, no solo como respuesta reactiva ante un problema ya detectado visualmente. Este método es simple, de bajo costo y permite cuantificar el defecto de forma objetiva antes de que el producto sea paletizado.
La tercera recomendación es implementar un registro histórico estructurado de eventos de desvío que incluya fecha, lote, turno, cantidad afectada y resolución. Con datos históricos acumulados sería posible detectar si el problema tiene estacionalidad, si está asociado a algún turno específico o a algún lote de materia prima, y anticipar futuros eventos antes de que ocurran.


---
# Herramientas utilizadas 
* Microsoft Excel fue utilizado para estructurar los datos de medición botella por botella, calcular el contenido neto real mediante el método gravimétrico, cuantificar el impacto operativo y económico del evento, y documentar el contexto, la metodología y los supuestos del análisis.
* Power BI Desktop fue utilizado para construir el dashboard interactivo con dos páginas. La primera presenta el análisis de calidad con los KPIs principales, el gráfico de contenido neto por botella comparado contra el límite legal, el volumen de cámara de aire por botella y la proporción de conformes versus no conformes. La segunda presenta el impacto operativo y económico con el impacto total estimado, la composición del costo del evento y el cuadro narrativo de conclusiones.

--- 
# Sobre este proyecto 
Soy Licenciada en Tecnología de Alimentos en transición hacia roles de Análisis de Datos. Este proyecto surge de un problema real que viví en la industria, donde aprendí que los datos no cambian lo que pasó, pero estructurarlos convierte un problema operativo en una decisión fundamentada.
Lo que este proyecto demuestra no es el uso de herramientas sofisticadas. Demuestra un proceso de pensamiento analítico: observar, estructurar, medir, cuantificar y recomendar. Ese proceso es transferible a cualquier industria y cualquier tipo de dato.


---
**Los datos de muestra son una combinación de mediciones reales tomadas durante el evento y valores simulados para completar la muestra representativa, declarados como tales en la documentación del proyecto. Los valores económicos son estimaciones de referencia basadas en parámetros típicos de la industria para el período 2023.**
