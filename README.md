# Análisis de Desvío de Calidad — Cámara de Aire en Aceto Balsámico Reducción 


---
# Problema de negocio
En un proceso de fraccionamiento de aceto balsámico (250 ml), se detectó un defecto visual en producto terminado: presencia de cámara de aire en botellas listas para despacho.
Este defecto implica que el contenido neto real es inferior al declarado en etiqueta, convirtiendo el producto en no conforme según normativa legal, lo que impide su comercialización.


---
#Impacto clave
* $2.858.000 ARS en pérdidas estimadas
* 2.712 botellas inmovilizadas durante 90 días
* 70% de las botellas fuera de especificación


---
# Dataset
* Muestra de 20 botellas del lote afectado
* Variables analizadas:
  * Contenido neto real
  * Volumen de cámara de aire
  * Límite legal de tolerancia
* Datos basados en mediciones reales + valores simulados para completar la muestra


---
# Análisis realizado
* Cálculo de contenido neto mediante método gravimétrico
* Comparación contra límite legal (237,5 ml)
* Análisis exploratorio para detección de patrones
* Clasificación de botellas en conformes / no conformes
* Extrapolación de resultados al lote completo


---
# Insights clave
* El defecto no es aleatorio, sino estructural
* El volumen de cámara de aire en botellas no conformes supera 3x el límite permitido
* El 70% del lote no cumple con especificaciones legales
* El 94,9% del impacto económico proviene del stock inmovilizado
* Botellas conformes también quedan retenidas por protocolo operativo


---
# Decisión de negocio
Implementar controles preventivos permite reducir significativamente el impacto económico.
Un control gravimétrico en línea tiene un costo bajo y permite detectar el problema antes de la inmovilización del lote.


---
# Recomendaciones
* Implementar control gravimétrico en línea
* Establecer período de reposo obligatorio antes de liberación
* Crear registro histórico de desvíos para análisis futuro


---
# Herramientas utilizadas
* Excel: limpieza, cálculo y estructuración de datos
* Power BI: visualización de KPIs y análisis del impacto


--- 
# Sobre el proyecto
Este proyecto surge de una experiencia real en industria alimentaria, donde un problema operativo fue transformado en un análisis de datos para cuantificar su impacto y fundamentar decisiones.
Demuestra un enfoque analítico basado en: estructuración de datos, análisis de patrones, generación de insights, toma de decisiones basada en datos

