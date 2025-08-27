1)Objetivo: Explorar cómo se distribuye el tráfico entre diferentes cinturones y vías principales (M-30, M-40, interior y exterior).
Visualizar tendencias y patrones mensuales mediante gráficos y heatmaps.
Predecir el tráfico del siguiente mes (mes 13) usando regresión lineal simple.
Identificar zonas más congestionadas y meses pico.

2)Fuente de los datos: Datos descargados del Portal de Datos Abiertos de Madrid (ver link dentro del notebook o .csv aqui en el repo)
Contienen tráfico promedio de vehículos en días laborables por zonas de la ciudad.

3)Metodologia: Se filtró solo el año 2024 para evitar filas con NaN.
Se reorganizó el dataset de formato ancho a largo (long format) con columnas: Mes, Zona, Trafico.
Se limpiaron nombres de zonas para consistencia.

4)Visualizaciones destacadas: Heatmap absoluto: muestra el tráfico promedio diario por zona y mes.
Heatmap porcentual: porcentaje de tráfico por zona respecto al total mensual.
Gráfico comparativo de evolución: comparación de M-30 vs Interior del 1er cinturón por meses.
Predicción del mes 13: tendencia lineal del tráfico y punto proyectado para el mes siguiente.
