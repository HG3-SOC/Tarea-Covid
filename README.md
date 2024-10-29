# Tarea del análisis espacial sobre fallecidos de Covid-19 a nivel provincial

En este análisis, se utilizó el Índice de Moran Local Bivariado para evaluar la autocorrelación espacial de los casos de COVID-19 entre los años 2021 y 2022 en diferentes provincias segun el criterio virológico utilizados para la confirmacion de la defunción. El análisis reveló patrones espaciales de incidencia de COVID-19, permitiendo identificar las áreas críticas (hotspots) y zonas de baja incidencia (cold spots) entre 2021 y 2022 en la que se diagnostico mediante la prueba virológico o molecular. 

Hallazgos principales:
- Ucayali: Alrededor de la ciudad de Pucallpa, que muestra una concentración significativa en rojo, indicando alta incidencia de COVID-19 en ambos años.
- Arequipa: Cerca de la frontera con Moquegua y Puno, se observa otra área en rojo que también representa un foco de alta incidencia.
- Lima y alrededores: Existen algunos puntos alrededor de Lima y áreas adyacentes con menor intensidad, pero con presencia de color rojo que también señala preocupación.

##  Contenido
- **Data**: Registro diario de muertes por Covid-19 en el Perú a nivel nacional durante el período 2020-2024. Encontrado en la Plataforma Nacional de Datos Abiertos (https://www.datosabiertos.gob.pe/dataset/fallecidos-por-covid-19-ministerio-de-salud-minsa).
- **Maps**: Mapa del Perú a nivel departamental y provincial. 
  

## Diccionario de datos
| *Variable*         | *Descripción*                                                                                         |
|----------------------|---------------------------------------------------------------------------------------------------------|
| *AÑO_FALLECIMIENTO*   | Fecha de fallecimiento que ocurre por covid-19.            |
| *DEPARTAMENTO*   | Departamento donde reside la persona fallecida por covid-19.             |
| *PROVINCIA*  | Provincia donde reside la persona fallecida por covid-19.                            |
| *CLASIFICACION_DEF*      | Criterios utilizados para la confirmacion de la defunción por covid-19                              |
| *Criterio virológico*      | Muerte en un caso confirmado de COVID-19 que fallece en los 60 días posteriores a una prueba molecular (PCR) o antigénica reactiva para SARS-CoV-2.|

Link del trabajo: https://colab.research.google.com/drive/1GIJDGAAx8j18UmACBqyqCSKEQFjcDlam?usp=sharing
