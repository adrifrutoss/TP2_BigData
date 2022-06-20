
# Proyecto Final de Big Data 

Este proyecto consta de dos componentes: 

1- Data Fetching: el script permite obtener una lista de las últimas menciones de un handle o hashtag en Twitter a través de su API. 

2- Analisis de sentimeintos: En esta parte del script se realiza un análisis del Dataset obtenido en el componente 1 usando TextBlob y Vader para obtener la polaridad y la subjetividad de los tweets. 

# Preprocesamiento de datos 
1. Primeramente se extrae las menciones del hashtag o keyword del que se desea obtener.
2. Se guarda en un archivo .csv para su posterior análisis.
3. Limpieza de tweets. Se remueven los emojis, las menciones, hyperlinks, RTs, nuevas lineas y signos de puntuación. 
4. Se calcula el sentimiento (negativo, positivo,neutro).
5. Se eliminan los tweets que no tienen menciones. 
6. Se guarda el analisis en un archivo .csv 
7. Se calcula los porcentajes de sentimiento. 
8. Se realizan los graficos correspondientes. 

# Construido con 
 • Google Colab 
 
 • Lenguaje de Programación : Python 

# Requisitos 

• Tener Python 3 instalado 

• IDE o Notebook para ejecutar el código fuente( Para el archivo ".ipynb" se puede utilizar Google Colab y para el archivo ".py" se recomienda Jupyter) 


