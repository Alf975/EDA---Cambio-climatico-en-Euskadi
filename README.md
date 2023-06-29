### Descripción

Este estudio tiene como objetivo estudiar la evolución del cambio climático en Euskadi desde 1970, empleando las técnicas aprendidas en el módulo de Data Analysis. Para ello se van a considerar datos de temperatura y pluviometría extraídos de la API de [Aemet](https://opendata.aemet.es/centrodedescargas/inicio), correspondientes a estaciones metereológicas ubicadas en las tres capitales vascas: Bilbao, San Sebastian, y Vitoria. 


### Fases del estudio

#### 1. Elección del tema

El tema del estudio es el cambio climático, pero considerando un ámbito geográfico reducido, y centrándonos en nuestra comunidad autónoma. Me parece importante saber en qué situación nos encontramos actualmente, y poder saber con datos cómo está cambiando el clima en este proceso de calentamiento global.

#### 2. Planteamiento de hipótesis

Actualmente estamos sufriendo una alteración del clima a nivel mundial, debido al efecto invernadero producido por los gases resultantes de la actividad humana y de la generación de energía con combustibles fósiles. Este efecto invernadero produce un calentamiento global, que se puede cuantificar por medio de los datos de multitud de estaciones metereológicas repartidas por todo el mundo. 
Se ha estimado que este calentamiento no debe superar los 1.5ºC respecto los niveles preindustriales, ya que tendría muy graves consecuencias tanto para el medio ambiente, como para el ser humano. Todas las previsiones indican que esto ocurrirá a lo largo de este siglo, pero recientes estudios afirman que puede suceder en esta misma década.

La primera hipótesis que se plantea es que, en el País Vasco, en 2023, ya se ha alcanzado el incremento de 1,5ºC respecto los niveles preindustriales.

La segunda hipótesis es que ha aumentado la frecuencia de los fenómenos metereológicos extremos. Estos fenómenos se valoran en el estudio considerando la frecuencia de las precipitaciones superiores a 30 l/m2, y de las temperaturas superiores a 30ºC.


#### 2. Búsqueda de datos

Aunque hay multitud de sitios web que proporcionan datos metereológicos, el que ofrece datos de mayor calidad, y en la cantidad necesaria para hacer un estudio fiable, es [Aemet](https://opendata.aemet.es/centrodedescargas/inicio). Se dispone de un histórico de datos metereológicos para las tres capitales vascas, desde 1970 hasta 2022. 


#### 3. Preprocesado de los datos

Una vez descargados los datos, han sido agrupados en tablas para su tratamiento. Afortunadamente había muy pocos elementos nulos, que fueron eliminados sin alterar la calidad del resto de los datos. 

#### 4. Análisis de los datos

El análisis ha consistido en:
* Determinación de valores estadísticos con los valores medios anuales
* Evolución de los valores de temperatura y precipitaciones con el tiempo
* Cálculo del calentamiento climático producido desde 1970 hasta nuestros días
* Contraste de los resultados obtenidos con la hipótesis planteada

Las tecnologías empleadas han sido:
- Procesado de los datos: [Python](https://www.python.org/)
- Herramientas de visualización: [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/) y [Plotly](https://plotly.com/)
- Exposición de resultados: [Canva](https://www.canva.com/)


