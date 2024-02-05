# Covid-19-Analysis
## GESTIÓN DE LA SALUD EN COLOMBIA, Desafíos que enfrenta ante el Covid-19
Una entidad gubernamental responsable de la gestión de la salud en Colombia enfrenta el desafío de comprender y analizar la propagación del COVID-19 para tomar decisiones informadas y eficaces en la gestión pandémica, analizar los datos relacionados con el COVID-19 y presentar insights a través de visualizaciones que respondan a preguntas clave.

"Análisis de datos de relacionados con el COVID-19 realizado por el equipo Latam (Data Scientist Jr)"

El objetivo principal es extraer insights clave de los datos y proporcionar información valiosa que brinde ayuda a la toma de desiciones al gobierno con respecto a estas situaciones pandémicas presentadas en los últimos tiempos.

## Herramientas utilizadas
- Colab
- Python
- Librerías:
  - Pandas
  - Numpy
  - Matplotlib
  - StringIO
  - sklearn

## Configuración del Ambiente
Se realizó el trabajo en google Colab con los siguientes pasos:
- Configuración del Ambiente
- Obtención y tratamiento de datos

El archivo COVID19_Analytics_Modelo.ipynb es el código escrito en colab el cual contiene todas las operaciones de analisis, limpieza de datos e Insights.
Los datos reportados a nivel mundial fueron extraidos de fuentes oficiales, https://covid19.who.int y https://population.un.org/

## Insights

### 0. ¿Cuál es la Población de Colombia en comparación con los países con más casos Covid?
![image](https://github.com/TigerXHero/Covid-19-Analysis/blob/main/images/0.png)

Conclusión:
- Colombia tiene una población de 50.19 millones, está muy parejo con respecto a los últimos 4 del top 10 más importantes a nivel global, pero China con 1421.85 millones e India con 1383.11 milllones son los países con mayor población mundial.
  
### 1. ¿Cómo ha evolucionado el Covid-19 en Colombia en comparación con el impacto observado a nivel global?
![image](https://github.com/TigerXHero/Covid-19-Analysis/blob/main/images/1.png)

Conclusión:
- Gráfica de dona: La distribución de casos covid es bastante baja con respecto a los países más importantes con un 0.8% de impácto, con casos reportados de 6.39 Millones
- Gráfica de líneas: A pesar de experimetnar un aumento significativo en el día 400 desde el inicio de la pandemia, la evolución de casos en Colombia se mantuvo bajo control en comparación con los países líderes.

### 2. ¿Cuál ha sido la evolución de los nuevos casos diarios reportados de Covid-19 en el país a lo largo del tiempo?
![image](https://github.com/TigerXHero/Covid-19-Analysis/blob/main/images/2.png)

Conclusión:
El gráfico muestra la evolución de los casos diarios reportadosde COVID-19 en Colombia desde noviembre de 2020 hasta
marzo de 2023. Como principal observación se encuentra una
alta densidad de casos a partir del mes de Abril hasta Julio del
año 2021 lo que podría indicar un periodo crítico en la transmisión
del virus, sin embargo la mayor cantidad de casos diarios
registrados en Colombia fue en el mes de Enero del
año 2022 con un total de 212.000 casos activos.

### 3. ¿Cuál es la evolución del índice de letalidad del Covid-19 en el país, comparado con los países con los índices históricos más elevados?
![image](https://github.com/TigerXHero/Covid-19-Analysis/blob/main/images/3.png)

Conclusión:
Colombia tiene una letalidad de 2.6% pero tuvo un pico de 4.61% en la pandemia en abril y mayo de 2020, lo que lo sitúa en el puesto 38 de los 194 países analizados.Su letalidad es superior a la media mundial, que es de 2.1%. Colombia tiene más de 4 millones de casos confirmados y más de 100 mil muertes, lo que lo convierte en uno de los países más golpeados por la pandemia muy próximos a los países con más letalidad.

### 4. Desde una perspectiva demográfica, ¿cuáles son las características que tienen un mayor impacto en el índice de letalidad de un país?

![image](https://github.com/TigerXHero/Covid-19-Analysis/blob/main/images/4.png)

Conclusión:
Según el analisis de importancia, la densidad poblacional destaca como
  la más influyente con promedio del 25%, seguida
  por la poblacion femenina con 24%.
  Esto sugiere que la densidad poblacional y
  la poblacion femenina son relevantes
  en la incidencia de la letalidad del Covid-19.
## CONCLUSIONES Y RECOMENDACIONES FINALES
### Conclusiones:

- Impacto en la Salud Pública:

La situación epidemiológica en Colombia ha sido significativa, con 6.39 millones de casos reportados, lo que representa una proporción considerable de la población (aproximadamente el 12.7%). Aunque la tasa de letalidad promedio se mantuvo en un nivel manejable del 2.6%, es crucial estar alerta ante el pico más alto observado del 4.6%.

- Comparación Internacional:

Al comparar con otros países como Corea del Sur, Italia y China entre otros del top 10 con mas casos, Colombia enfrenta desafíos similares en términos de manejo de la pandemia. Es esencial aprender de las estrategias exitosas implementadas en países con poblaciones similares.

- Evolución Temporal:

La evolución de los casos diarios en Colombia muestra variaciones mensuales, siendo julio de 2021 y febrero de 2022 los meses más críticos con un poco más de 200 mil casos reportados. Este patrón destaca la necesidad de medidas específicas según la dinámica temporal de la enfermedad.

- Letalidad Comparativa:

A pesar de mantener una letalidad promedio del 2.6%, Colombia debe prestar atención al incremento en el pico de letalidad al 4.6%. Comparativamente, el país ha tenido un mejor desempeño que México, Perú, Sudán y Siria, lo que puede atribuirse a las intervenciones eficaces en el sistema de salud.

### Recomendaciones:

- Fortalecimiento de Medidas Preventivas:

Reforzar las medidas de prevención, especialmente en meses críticos, para evitar picos excesivos de casos. La comunicación efectiva y la participación comunitaria son clave.

- Análisis de Estrategias Exitosas:

Estudiar las estrategias implementadas en otros países como Corea del Sur, Noruega, Nueva Zelanda, que han demostrado ser efectivas en el control de la propagación del virus. Adaptar las mejores prácticas a la realidad colombiana puede mejorar la gestión de la crisis.

- Capacitación del Personal de Salud:

Proporcionar capacitación continua al personal de salud para mantener altos estándares en la atención médica, especialmente durante picos de casos y letalidad. La gestión eficiente de recursos y la respuesta rápida son cruciales.

- Enfoque en la Densidad Poblacional:

Considerar la densidad poblacional como un factor clave al diseñar estrategias específicas. Implementar medidas adaptadas a áreas más densamente pobladas para abordar posibles desafíos logísticos y de atención médica.

- Monitoreo y Evaluación Constantes:

Establecer un sistema robusto de monitoreo y evaluación para evaluar la efectividad de las intervenciones y ajustar estrategias según la evolución de la situación epidemiológica.

- Promoción de la Salud Femenina:

Dada la relevancia de la población femenina en la demografía, implementar programas de salud específicos que aborden las necesidades y preocupaciones de las mujeres, asegurando una respuesta integral a la pandemia.

Estas conclusiones y recomendaciones se basan en el análisis de los datos proporcionados y buscan orientar las acciones futuras de la entidad gubernamental de salud en Colombia para enfrentar la pandemia de manera efectiva y centrada en la salud pública.

## Autores

- [@Brusly]()
- [@Isaias](isaiasxhero)
- [@Jorge]()
- [@Jhordan]()
