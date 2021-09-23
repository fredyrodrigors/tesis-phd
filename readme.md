# Propuesta de un modelo de desambiguación léxica automática
Este repositorio contiene todos los documentos *.txt, *.csv, *.xml y *.xsl, correspondientes tanto al montaje del corpus como a los resultados de la investigación "Diseño y desarrollo de un modelo de desambiguación léxica automática para el procesamiento del lenguaje natural" (Posgrado en Lingüística de la Pontificia Universidad Católica de Chile).

## Experimento Senseval-3
El corpus utilizado para la tarea de muestra léxica del español en <a href="http://web.eecs.umich.edu/~mihalcea/senseval/"> SENSEVAL-3</a> está formado por 12.625 ejemplos etiquetados, que cubren 25.875 frases y 1.506.233 palabras en total. El contexto considerado para cada ejemplo incluye la palabra objetivo, más una ventana contextual. Todos los ejemplos han sido extraídos desde el corpus del año 2000 de la Agencia Española de Noticias EFE, que incluye 289.066 noticias (2.814.291 frases y 95.344.946 palabras), de enero a diciembre de 2000. Para cada palabra, un mínimo de 200 ejemplos han sido etiquetados manualmente por tres anotadores humanos expertos independientes. Los casos de desacuerdo han sido resueltos por otro lexicógrafo (asignando un sentido único a cada ejemplo). Para la ejecución del experimento de prueba de aprendizaje automático utilizando el algoritmo bayesiano ingenuo, se seleccionaron 120 instancias de la  muestra léxica para la palabra objetivo «partido», extraída desde el corpus SENSEVAL-3. 

- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/partido_minidir_senseval.xml">Minidiccionario para los sentidos de «partido»</a> 
- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/partido_instancecorpus_senseval.xml">Corpus de 120 instancias para cada uno de los sentidos de «partido»</a>

### Resultados de los experimentos de pilotaje para las medidas de reducción de dimesión

**1. "partido.1" =  Organización política cuyos miembros comparten la misma ideología**
- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/resultados_partido1_chisquare.csv">"partido.1" para chi-cuadrado</a>
- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/resultados_partido1_informationgain.csv">"partido.1" para ganancia de información</a>
- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/resultados_partido1_mutualinformation.csv">"partido.1" para información mutua</a>

**1. "partido.1" =  Organización política cuyos miembros comparten la misma ideología**
- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/resultados_partido2_chisquare.csv">"partido.2" para chi-cuadrado</a>
- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/resultados_partido2_informationgain.csv">"partido.2" para ganancia de información</a>
- <a href="https://github.com/fredyrodrigors/tesis-phd/blob/main/experimento_senseval-3/resultados_partido2_mutualinformation.csv">"partido.2" para información mutua</a>




## Experimento CODICACH



