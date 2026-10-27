# Informe Tecnico
## 1. Introducción
La brecha digital se refiere a las diferencias en el acceso, uso y aprovechamiento de las tecnologías de la información y la comunicación (TIC)
entre personas, hogares y territorios. 
En Argentina, la brecha digital puede estar relacionada con diversos factores socioeconómicos, educativos y geográficos, 
que influyen en las posibilidades de los hogares de acceder a internet y contar con equipamiento informático.
En este contexto, el presente proyecto se desarrolla como un diagnóstico para una organización gubernamental de desarrollo social y tecnología. 
El objetivo principal de la organización es evaluar las desigualdades en el acceso de los hogares a internet fijo y computadoras, 
considerando factores socioeconómicos, educativos y geográficos. 
Los resultados buscan aportar información que contribuya al diseño de políticas públicas de inclusión tecnológica 
y a la planificación de inversiones en infraestructura.
Para llevar a cabo el estudio, se utiliza un conjunto de datos simulados, basado en variables de la Encuesta Permanente de Hogares (EPH) del INDEC y generado mediante un código proporcionado por la cátedra.
El análisis se realiza mediante Python en Google Colab, aplicando técnicas de limpieza, procesamiento y análisis exploratorio de datos.
## 2. Marco Teórico
### 1. Concepto de brecha digital

La brecha digital se refiere a las desigualdades en el acceso, uso y aprovechamiento de las tecnologías de la información y la comunicación (TIC). Estas diferencias no dependen únicamente de la disponibilidad de dispositivos y conexión a Internet, sino también de factores sociales, económicos y educativos que condicionan las oportunidades de acceso (OCDE, 2001; van Dijk, 2005).

### 2. Dimensiones de la brecha digital

La brecha digital puede analizarse desde tres dimensiones principales:

* Social y territorial: contempla las diferencias entre regiones y hogares en el acceso a las tecnologías.
* Económica: considera cómo los ingresos familiares condicionan la posibilidad de adquirir dispositivos y contratar servicios de Internet.
* Educativa: analiza la relación entre el nivel educativo y las desigualdades en el acceso y aprovechamiento de las TIC.

Estas dimensiones se relacionan entre sí y pueden contribuir a reproducir desigualdades sociales preexistentes.

###3. Fundamentos teóricos

La investigación se basa en el enfoque de la desigualdad social, que permite estudiar cómo los recursos y las oportunidades se distribuyen de manera desigual entre la población. También considera la teoría del capital humano de Becker (1964), que destaca la importancia de la educación y las habilidades en el desarrollo de oportunidades individuales.
Estos enfoques permiten analizar cómo las condiciones económicas, educativas y territoriales se relacionan con el acceso a las tecnologías.

###4. Definición de las variables

El análisis utiliza microdatos de la Encuesta Permanente de Hogares (EPH) del INDEC. Las variables seleccionadas son:

* REGION: identifica la región geográfica y permite comparar diferencias territoriales.

* IX_TOT: indica la cantidad de integrantes del hogar y permite considerar su tamaño.

* NIVEL_ED: representa el nivel educativo y permite estudiar su relación con las desigualdades digitales.

* ITF: corresponde al ingreso total familiar y permite analizar las diferencias económicas.

* DECIFR: identifica el decil de ingreso familiar, lo que permite comparar hogares según su posición en la distribución de ingresos.

* IV12_3: indica si el hogar dispone de computadora o laptop.

* II7: indica si el hogar dispone de conexión fija a Internet.

Las variables IV12_3 e II7 permiten estudiar el acceso a dispositivos y conectividad, mientras que las restantes aportan información sobre las condiciones sociales, económicas y educativas de los hogares.

###5. Relación con la investigación

El objetivo es analizar las desigualdades regionales y socioeconómicas en el acceso a las tecnologías en Argentina. Se buscará identificar si la disponibilidad de computadoras e Internet fija presenta diferencias según los ingresos, el nivel educativo y la región. Los resultados permitirán reconocer patrones de desigualdad, sin asumir relaciones causales que los datos no permitan demostrar.
