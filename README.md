# Text Mining in Social Media
Trabajo del Máster Big Data Analytics (UPV) sobre Text Mining

En este trabajo se ha creado un modelo de clasificación, predicción y evaluación del sexo y de la variedad del español de usuarios de twitter a partir de 100 de sus tuits. Se ha usado el DataSet PAN-AP’17, preparado y clasificado en dos particiones, train y test. 

La aproximación principal al problema ha sido el uso de una bolsa de palabras ponderada basada en TF-IDF (term frequency - inverse document fre- quency) que da más importancia a las palabras que se usan solamente en un documento, frente a las demás.

Se realizaron otras aproximaciones como la del cálculo de la longitud de los tuits, basándonos en la hipótesis de que las mujeres escriben de media tuits más largos que los hombres. 

Por otra parte, se construyó una bolsa de palabras ponderada al modo TF-IDF por sexos, donde se pueden ver resultados interesantes: las palabras más usadas por los hombres que usan las mujeres, y viceversa. En las siguientes imágenes se muestran dos gráficos de nubes de palabras. ¿Sabrías adivinar cuál corresponde a los hombres, y cuál a las mujeres?



