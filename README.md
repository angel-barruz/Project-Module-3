# Proyecto M贸dulo 3

# 馃懚 Status
https://github.com/angel-barruz/Project-Module-3


馃弮  Description

El objetivo del proyecto es predecir el precio, entrenando el Database competi_kaggle de Diamonds, respecto al Dataset de Diamnods test de Kaggle.


# 馃捇 Workflow

Realizamos EDA para analizar los datos.

1- Cargamos el DataFrame que utilizamos en el lab de Diamonds

    1.1 Preprocesing
    1.2 Feature Engennering

2 - Modificaci贸n de variables. Probamos en funci贸n a la correlaci贸n de las variables.

3 - Establecemos en la variable X las features y en la variable y el target

4 - One hot encoding: convertimos las varibles de tipo discretas a binarias y asi preparar el modelo para entrenarlo, ya que solo entiende n煤meros y no categor铆as.

5 - Scaling: normalizamos el valor de las variables para que las variables de tipo cont铆nuas se asemejen a las binarias.

6 - Model Definition: seleccionamos el algoritmo que consideramos 贸ptimo para el modelo (RandomForest) para entrenarlo posteriormente con nuestro DataFrame escalado. Para optimmizarlo, modificamos hiperpar谩metros.

7 - Model Training: entrenamos los datos de nuestro DataFrame con el algoritmo elegido

8- Metrics Analyses

    Train test split: usamos este m茅todo de entrenamiento para posteriormente realizar mediciones
    MSE: Error cuadr谩tico m茅dio, para el c谩lculo del error
    RMSE: Desviaci贸n del error cuadr谩tico medio

9 -Kaggle

    9.1 Cargamos el DataFrame que nos da Kaggle . Este no contiene la columna precio.
    9.2 Repetimos el proceso de One hot Encoding con los datos del Dataframe de Kaggle
    9.3 Repetimos el proceso de Scaling con los datos del Dataframe de Kaggle
    9.4 Predecimos (.predict) sobre el modelo entrenado (.fit) para sacar el target

10 - Guardamos en csv la predicci贸n del precio

11 - Subimos nuestra predicci贸n de Precio para que lo puntue Kaggle en funci贸n al precio de Kaggle "real"

12 - La predicci贸n se valorar谩 en funci贸n al RMSE del precio que desconocemos de Kaggle para que se situe en el Ranking


# 馃挜 Best Model

De los dos modelos seleccionados que son:

1 - Modelo 1 Competi de Kaggle, con RMSE en Jupyter Notebook de 230,79 y en Kaggle 655 de RMSE
2 - Modelo 2 Competi de Kaggle, con RMSE en Jupyter Notebook de 232,91 y en Kaggle 622,66 de RMSE



# 馃檲 Analysis

La conclusi贸n a  la que podemos llegar  es que nuestro modelo tiene Overfiting, ya que el RMSE en Jupter Notebook, respecto al RMSE de Kaggle, tiene 400 puntos de diferencia aproximadamente.



# 馃拰 Contact info
脕ngel Barruz Montalvo
Tel: 680 50 57 51
email: a.barruz@gmail.com
