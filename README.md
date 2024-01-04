# Descripción del Repositorio
El análisis de las bases se hizo a través de un programa en R Studio, el cual nos permitió ver las características dentro de las bases de cada una de las variables del SARS COVID-19 disponibles en la base de datos de PubMed.

# Análisis Parte 1:

## Situación Actual
Durante el último mes, según el reporte de la OMS en relación al estado actual de nuestra sociedad con el virus, se reportaron aproximadamente 2.8 millones de casos nuevos, mientras que se registraron solamente 16,000 muertos a lo largo del globo. Estas cifras son alarmantes, ya que los índices de contagios se habían reducido en los últimos años, representando estos datos un riesgo para la salud pública global. Los contagios se reportaron mayormente en la parte sureste del continente Asiático.

Aunque las cifras han sido altas en otros continentes, el riesgo epidemiológico dentro de América se ha reducido de manera notable desde el último año, gracias a las condiciones donde se desarrollan las personas. Igualmente el riesgo de muerte se ha equilibrado durante el útlimo año gracias al avance tecnológico que se ha tenido, ya que aunque los casos de contagios son mayores, la tasa de muerte se ha reducido a más de la mitad desde el año pasado, donde aún se presentaba como un riesgo público.

Estos datos igualmente aplican para México, donde se enfrenta a diversos casos de contagios, buscando reducirlos lo más que se pueda. Mientras que la tasa de contagio está en constante crecimiento, la tasa de muertes se mantiene estable según los datos dados por el CONACYD.

Dentro del estado de Puebla, se ha logrado controlar los estados de contagios por lo cual las medidas preventivas impuestas por el gobierno fueron removidas, y de igual manera se buscó dejar el uso del cubrebocas dentro de las actividades del día a día, aplicando la norma hacia todas las colonias y municipios de la ciudad, ya que por épocas de lluvia, se prioriza el evitar contagios de bacterias que puedan representar un riesgo sanitario por las inundaciones causadas por presas y ríos localizados alrededor del estado.

## Variantes del SARS-CoV-2
Dentro del desarrollo del virus, han existido diversas variaciones del virus que han representado un riesgo para la humanidad. A continuación se enlistan las principales variantes del virus SARS-CoV-2 de manera cronológica:

• Variante de Wuhan (China) - Diciembre de 2019, Wuhan, China: Es la variante original del virus SARS-CoV-2.
• Variante BETA - Mayo de 2020, Sudáfrica: Presenta una mutación en la proteína S que puede hacerla más contagiosa y resistente a los anticuerpos, pero parece que las vacunas son efectivas contra ella.
• Variante EPSILON - Julio de 2020, California, Estados Unidos: Aunque se necesitan más estudios, se ha sugerido que podría ser más contagiosa y resistente a las vacunas.
• Variante ALPHA - Septiembre de 2020, Reino Unido: Se ha propagado a nivel mundial. Presenta una mutación en la proteína S que facilita su transmisión, pero parece responder a las vacunas.
• Variante DELTA - Diciembre de 2020, India: Se cree que es altamente transmisible y que puede reducir la efectividad de algunas vacunas.
• Variante MU - Enero de 2021, Colombia: Presenta mutaciones en la proteína S que podrían reducir la efectividad de las vacunas, pero todavía se necesita más investigación para entender su impacto.
• Variante ETA - Abril de 2021, Europa: Su impacto y características son desconocidas.
• Variante KAPPA - Abril de 2021, India: Se cree que puede ser más transmisible que la variante original, pero su impacto y características aún se están estudiando.
• Variante ZETA - Abril de 2021, Brasil: Aunque se necesita más investigación, se cree que puede ser más transmisible que la variante original del virus.
• Variante TAU - Agosto de 2021, Colombia: Presenta mutaciones en la proteína S que podrían afectar la eficacia de algunas vacunas, pero se necesita más investigación para entender su impacto.
• Variante OMICRON - Noviembre de 2021, Sudáfrica: Presenta un gran número de mutaciones en la proteína S y se cree que es altamente transmisible. Se necesitan más estudios para comprender su impacto y características.

## Métodos de Investigación y Casos Hipotéticos
Para la investigación del virus, usaría yo fuentes de confianza, como reportes emitidos por organizaciones gubernamentales o de carácter global, aunque por la corrupción y la apatía dentro de México, estos no son del todo certeros, y por lo tanto, no podemos tener estadísticas específicas acerca de cómo se desarrolla nuestro entorno. Igualmente me iría a reportes de investigación de carácter científico emitidos por reconocidos investigadores, para así poder saber acerca de las características de las variantes, así complementando mi investigación con las noticias locales, y mundiales para poder tener un contexto amplio alrededor de lo sucedido afuera.

Alrededor de las investigaciones del virus, al principio se trató de silenciar esta noticia, el cual fue descubierto por Li Wenliang, y fue silenciado por su propio gobierno. Si estuviera yo en su caso, conociendo las condiciones políticas y gubernamentales de China, trataría de recurrir a centros de investigación y universidades para requerir un apoyo, aunque lo trataría de hacer de manera global para así no tener censura del caso, permitiendo que otras personas puedan ayudar a solucionar este tipo de casos, evitando una catástrofe dentro de nuestra sociedad.

# Análisis Parte 2:

## Programación para Software de Análisis de Bases
Para el proyecto, se ha creado un programa para el análisis de las bases de cada una de las variantes, usando los datos obtenidos dentro de la Librería Nacional de Medicina (NCBI), importando los datos de cada una de estas de la sección de Genes, como archivos “fasta”. De esta manera, creamos funciones para poder contar el largo de las secuencias (lenght()), haciendo uso de las tablas incluidas en los archivos, y la lectura de los mismos para el análisis individual de los nucleótidos, y de igual forma la construcción de las estructuras con los primeros y últimos 20 nucleótidos usando las funciones de “head()” y “tail()”. Después de esto, se creó una tabla, conteniendo el porcentaje de los nucleótidos de cada variante, así permitiéndonos hacer un gráfico que nos determina el porcentaje en cada uno de los nucleótidos encontrados, así analizando los componentes de la estructura de cada uno para entender sus características que lo hacen diferente al resto, buscando entender estas estructuras para la creación de vacunas y anticuerpos para el ser humano. Dentro del mismo se incluye una explicación del gráfico.

