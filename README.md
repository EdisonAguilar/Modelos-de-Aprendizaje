﻿# Modelos-y-Aprendizajes
 Trabajo Final - Modelos y Aprendizajes:

En este programa busca hacer un webscrapper (con un archivo-dataset) a una pagina web, que es la pagina publicada como reto, se me ocurrio la idea de ingresar a la pagina, navegar en la misma y descargar el archivo , configurar la ruta de descarga con la de carpeta de mi proyecto,( estoy conciente que estos archivos deberan borrarse a futuro para no causar problemas de reemplazo de archivos), asi mismo te ire detallando las acciones que fui realizando como comentarios dentro del codigo para al final llegar a la conclusion con los resultados obtenidos en base a las matrices de confusion de cada modelo. 
Saludos.. Edison

De los modelos evaluados, estan el modelo lineal SGDC, el modelo KNN, el modelo de arbol de decision y el algoritmo de modelo Random Forest, en cada unos delllos mediante el analisis
de su matriz de confusion tanto en test como en train se busca una mayor precision y exactitud.
RESULTADOS de los principales modelos:
Modelo SGDC: el modelo de Machine Learning escogido no detecta la clase muy bien, pero cuando lo hace es altamente confiable, el problema es que de acuerdo a la simulaciones, algunas veces se tiene resultados muy buenos ,
y en otras resultados muy deficientes, y en este caso se ha dejado la constancia de ello en la cual alrededor del 50% de la muestra es incorrectamente categorizada.

Modelo Random Forest:Este El modelo de Machine Learning escogido,logra clasificar la clase correctamente sin embargo incluye cierto numero de muestras de la otra clase, no son grandes errores
se aprecia un modelo bastante aceptable pero que no da la certeza de ser nuestro modelos final.

*Modelo de Arbol de decision(Mejores resultados):El modelo de Machine Learning escogido detecta bien la clase,con un menor error de categorizacion de clase en relacion a los demas modelos, funciona de mejor manera que el modelo Random Forest que presenta resultados similares, pero al tener mayor precision tanto en train como en test , con una diferencia de 97%/92% vs 95%/89 tanto en train como en test respectivamente, 
por esta razon se considera la utilizacion del modelo de arboles de decision como el que nos presenta mejores resultados segun el planteamiento que hemos realizado.

**Como detalle adicional segun los resultados obtenidos cuando se implementan ambos modelos que nos dieron resultados aceptables, ambos algoritmos están expuestos al sobreajuste, lo que crea una situación de incertidumbre y tiempos altos mientras se entrenan los datos. 
En tales escenarios, un árbol de decisión tiene más posibilidades de sobreajuste. En cambio, el algoritmo random forest puede reducir esta exposición con múltiples árboles y si se cuenta con una maquina con buen procesamiento se puede crear modelos mas avanzados y emplear Random Forest.



