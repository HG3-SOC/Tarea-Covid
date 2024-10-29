# Tarea del análisis espacial sobre fallecidos de Covid-19 a nivel provincial

##  Descripción del análisis
En este análisis, se utilizó el Índice de Moran Local Bivariado para evaluar la autocorrelación espacial de los casos de COVID-19 entre los años 2021 y 2022 en diferentes provincias segun el criterio virológico utilizados para la confirmacion de la defunción. El análisis reveló patrones espaciales de incidencia de COVID-19, permitiendo identificar las áreas críticas (hotspots) y zonas de baja incidencia (cold spots) entre 2021 y 2022 en la que se diagnostico mediante la prueba virológico o molecular. 

Hallazgos principales en 2021:
- Ucayali y Amazonas: En estos departamentos se muestra que en algunas provincias hay una concentración significativa en rojo, indicando alta incidencia de fallecidos de COVID-19 que fueron diagnosticodos mediante la prueba virológico.

Hallazgos principales hasta 2022:

- Ucayali y Loreto: La provincia de Padre Abad en Ucayali está en rojo, indicando un hotspot de COVID-19 detectado con prueba molecular. Esto sugiere una alta concentración de fallecimientos en esta área que fueron diagnosticagos por la prueba molecular.
- Arequipa y Cusco: La zona está coloreada en negro (coldSpot), lo que indica una baja incidencia en comparación con otras provincias. Este cold spot sugiere que en esta área la deteccion del virus con la prueba molecular fue menos intensa, lo que podría ser un reflejo de sus medidas de control
- Tacna y Puno: Se muestra áreas en rojo, destacándose como un hotspot. Esto indica que en esta región hubo una alta incidencia de fallecimientos por COVID-19 detectados con la prueba molecular. También se observan zonas verdes en Tacna y Moquegua (coldOutliers), sugiriendo áreas con menor impacto en medio de una región con alta incidencia.

##  Data
- **Enfermedad**: Registro diario de muertes por Covid-19 en el Perú a nivel nacional durante el período 2020-2024. Encontrado en la Plataforma Nacional de Datos Abiertos (https://www.datosabiertos.gob.pe/dataset/fallecidos-por-covid-19-ministerio-de-salud-minsa).
- **Mapas**: Mapa del Perú a nivel departamental y provincial. 
  

## Diccionario de datos
| *Variable*         | *Descripción*                                                                                         |
|----------------------|---------------------------------------------------------------------------------------------------------|
| *AÑO_FALLECIMIENTO*   | Fecha de fallecimiento que ocurre por covid-19.            |
| *DEPARTAMENTO*   | Departamento donde reside la persona fallecida por covid-19.             |
| *PROVINCIA*  | Provincia donde reside la persona fallecida por covid-19.                            |
| *CLASIFICACION_DEF*      | Criterios utilizados para la confirmacion de la defunción por covid-19                              |
| *Criterio virológico*      | Muerte en un caso confirmado de COVID-19 que fallece en los 60 días posteriores a una prueba molecular (PCR) o antigénica reactiva para SARS-CoV-2.|

Link del trabajo: https://colab.research.google.com/drive/1GIJDGAAx8j18UmACBqyqCSKEQFjcDlam?usp=sharing
