# Ciencia de Datos en Python
## Hoja_Trabajo_No.3

### Programación Orientada a Objetos:

##### 1. Constructor Principal: 
este constructor debe poseer la siguiente forma _ _init_ _ (self, x, y) donde X y Y son listas de números con la misma cantidad de elementos.
A partir de este constructor usted deberá calcular los parámetros β0 y β1.

##### 2. Método Predict(val):
Este método devuelve la predicción de la regresión aplicada sobre el valor que recibe como parámetro. 

##### 3. Método PredictN(vals):
Este método devuelve la predicción de la regresión aplicada sobre una lista de valores que recibe como parámetro. 

##### 4. Método r2 ():
Este método calcula el r2 (coeficiente de determinación) de la regresión.

##### 5. Método r ():
Este método devuelve el coeficiente de correlación el cual se calcula como la raíz cuadrada el coeficiente de determinación.

##### 6. Método getAllRegParams ():
Este método devuelve un diccionario con todos los parámetros y estadísticos de la regresión línea.

##### 7. Constructor from file(fileName):
Este método es otro constructor el cual permite crear la regresión lineal a partir de un archivo .csv.
Dentro del archivo deben existir dos columnas, la primera es la variable dependiente es decir Y y la segunda se refiere a los valores de la variable independiente, es decir X regresión desde dos listas numeradas. 
