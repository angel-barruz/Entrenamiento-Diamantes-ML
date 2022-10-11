# Proyecto Módulo 3

# 👶 Status
https://github.com/angel-barruz/Project-Module-3


🏃  Description

El objetivo del proyecto es predecir el precio, entrenando el Database competi_kaggle de Diamonds, respecto al Dataset de Diamnods test de Kaggle.


# 💻 Workflow

Realizamos EDA para analizar los datos.

1- Cargamos el DataFrame que utilizamos en el lab de Diamonds

    1.1 Preprocesing
    1.2 Feature Engennering

2 - Modificación de variables. Probamos en función a la correlación de las variables.

3 - Establecemos en la variable X las features y en la variable y el target

4 - One hot encoding: convertimos las varibles de tipo discretas a binarias y asi preparar el modelo para entrenarlo, ya que solo entiende números y no categorías.

5 - Scaling: normalizamos el valor de las variables para que las variables de tipo contínuas se asemejen a las binarias.

6 - Model Definition: seleccionamos el algoritmo que consideramos óptimo para el modelo (RandomForest) para entrenarlo posteriormente con nuestro DataFrame escalado. Para optimmizarlo, modificamos hiperparámetros.

7 - Model Training: entrenamos los datos de nuestro DataFrame con el algoritmo elegido

8- Metrics Analyses

    Train test split: usamos este método de entrenamiento para posteriormente realizar mediciones
    MSE: Error cuadrático médio, para el cálculo del error
    RMSE: Desviación del error cuadrático medio

9 -Kaggle

    9.1 Cargamos el DataFrame que nos da Kaggle . Este no contiene la columna precio.
    9.2 Repetimos el proceso de One hot Encoding con los datos del Dataframe de Kaggle
    9.3 Repetimos el proceso de Scaling con los datos del Dataframe de Kaggle
    9.4 Predecimos (.predict) sobre el modelo entrenado (.fit) para sacar el target

10 - Guardamos en csv la predicción del precio

11 - Subimos nuestra predicción de Precio para que lo puntue Kaggle en función al precio de Kaggle "real"

12 - La predicción se valorará en función al RMSE del precio que desconocemos de Kaggle para que se situe en el Ranking


# 💥 Best Model

De los dos modelos seleccionados que son:

1 - Modelo 1 Competi de Kaggle, con RMSE en Jupyter Notebook de 230,79 y en Kaggle 655 de RMSE
2 - Modelo 2 Competi de Kaggle, con RMSE en Jupyter Notebook de 232,91 y en Kaggle 622,66 de RMSE



# 🙈 Analysis

La conclusión a  la que podemos llegar  es que nuestro modelo tiene Overfiting, ya que el RMSE en Jupter Notebook, respecto al RMSE de Kaggle, tiene 400 puntos de diferencia aproximadamente.



# 💌 Contact info
Ángel Barruz Montalvo
Tel: 680 50 57 51
email: a.barruz@gmail.com
