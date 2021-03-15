# Proyecto_Python_Transporte_CDMX
![capa](https://user-images.githubusercontent.com/71915068/110401847-fb291280-803f-11eb-83ee-ad6e9708913a.png)

## Contenido

### 1.Planteamiento del Problema
- Preguntas Clave
### 2.Extracción de datos
- Descripción de las Columnas
- Exploración básica de datos
  - Trip duration 
  - dist_meters
  - wait_sec
- Hallazgos preliminares encontraros
### 3.Limpieza de datos y agregaciones
- Chequeo NaN's
- Eliminación de columnas
- Casting fechas
- Conversión de unidades
- Eliminación de outlayers
  - speed_km
  - dist_km
  - trip_duration
  - wait_sec
  - Resumen posterior a eliminación de outliers
- Resultados limpieza
### 4.Api GeoNames
- Reverse Geocoding
  - Función de petición  GET
- Concatenación de latitud y longitud
- Proceso de conversión de coordenadas
- Eliminación de viajes fuera de la Zona Metropolitana del Valle de México
- Exportación de DataFrame resultante
### 5.Tarifas y Costos
- Tarifas
- Costos
- Aplicación de Tarifa Mínima
- Agrupaciones por mes, días y horas
  - Separación de Fecha en Hora, Día, Mes
  - Resultados
### 6.Análisis Exploratorio
- Clasificando los viajes
- Viajes por origen y destino
- Tiempo de espera la misma alcaldia
- Viajes solo por Taxis
- Viajes solo por Ubers
- Origen de los viajes
  - Taxis
  - Ubers
- Destino de los viajes
  - Taxis
  - Ubers
- Análisis de tiempo de espera promedio en los viajes por día
- Análisis de cantidad de viajes por cada día de la semana
- Comparación de tiempo detenido en el tráfico por viaje en Taxis y Ubers
- Velocidad Promedio por cada tipo de transporte
- Conclusión 
