# Proyecto Módulo 1

# 👶 Status
https://github.com/angel-barruz/Project-Module-3


🏃  Description

El objetivo del proyecto es predecir el precio, entrenando el Database de Diamonds que trabajamos en el lab correspondiente, respecto al Dataset de Diamnods de Kaggle.

# Resources

Librerías:

    import numpy as np
    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns

    from sklearn import datasets
    from sklearn.datasets import make_regression
    from sklearn.model_selection import train_test_split
    import pickle
    import joblib

    from sklearn import linear_model
    from sklearn.linear_model import ElasticNet
    from sklearn.linear_model import Ridge
    from sklearn.svm import SVR
    from sklearn.linear_model import SGDRegressor
    from sklearn.linear_model import LinearRegression
    from sklearn.ensemble import RandomForestRegressor

    from sklearn.metrics import mean_squared_error

    from sklearn.preprocessing import StandardScaler

    from sklearn import preprocessing



# 💻 Workflow

1- Cargamos el DataFrame que utilizamos en el lab de Diamonds

2 - Modificación de variables. Probamos en función a la correlación de las variables.

3 - Establecemos en la variable X las features y en la variable y el target

4 - One hot encoding: convertimos las varibles de tipo discretas a binarias y asi preparar el modelo para entrenarlo, ya que solo entiende números y no categorías.

5 - Scaling: normalizamos el valor de las variables para que las variables de tipo contínuas se asemejen a las binarias.

6 - Model Definition: seleccionamos el algoritmo que consideramos óptimo para el modelo para entrenarlo posteriormente con nuestro DataFrame escalado. Para optimmizarlo, tenemos la opción de modificar hiperparámetros.

7 - Model Training: entrenamos los datos de nuestro DataFrame con el algoritmo elegido

8- Mediciones

    Train test split: usamos este método de entrenamiento para posteriormente realizar mediciones
    MSE: Error cuadrático médio, para el cálculo del error
    RMSE: Error

9 -Kaggle

    9.1 Cargamos el DataFrame que nos da Kaggle . Este no contiene la columna precio.
    9.2 Repetimos el proceso de One hot Encoding con los datos del Dataframe de Kaggle
    9.3 Repetimos el proceso de Scaling con los datos del Dataframe de Kaggle
    9.4 Predecimos (.predict) sobre el modelo entrenado (.fit) para sacar el target

10 - Guardamos en csv la predicción del precio




# 💥 Core 

11 - Subimos nuestra predicción de Precio para que lo puntue Kaggle en función al precio de Kaggle "real"

12 - La predicción se valorará en función al RMSE del precio que desconocemos de Kaggle para que se situe en el Ranking
    
# 🔧 Best Model



# 🙈 Analysis











# 💌 Contact info
Ángel Barruz Montalvo
Tel: 680 50 57 51
email: a.barruz@gmail.com
