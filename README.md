# Prediccion-de-Precios-de-Mochilas-usando-Modelos-de-Machine-Learning

## Descripción del Proyecto

Este proyecto busca predecir el precio de mochilas en función de sus características, como la marca, material, tamaño, estilo y capacidad de peso. Se exploraron y compararon diferentes modelos de regresión para encontrar el que mejor se ajusta a los datos.

## Objetivo
Desarrollar un modelo de Machine Learning capaz de estimar los precios de mochilas en base a sus atributos.

## Modelos Evaluados
Se probaron los siguientes modelos:

* Árbol de Decisión 
* Gradient Boosting 
* CatBoost

## Las métricas utilizadas para evaluar los modelos fueron: MSE, RMSE, MAE y R2.

|Modelo|	MSE|	R2|	RMSE|	MAE|
|:-----|:-----|:-----|:-----|:-----|
|Árbol de Decisión|	1516.11|	0.0003|	38.93|	33.66|
|Gradient Boosting|	1514.82|	0.0011|	38.92|	33.64|
|CatBoostRegressor|	1515.05|	0.0010|	38.92|	33.65|

## Conclusiones

* El MSE es similar en los tres modelos. Lo que quiere decir que tienen el mismo rendimiento.
* El RMSE es relativamente alto lo que indica que el modelo no esta haciendo predicciones precisas.
* El R2 en los tres modelos es muy cercano a cero lo que indica que el modelo no esta explicando practicamente nada.
* El MAE tambien es alto,osea las prediciones se desvian 33.6 aproximadamente.
* Los tres modelos tienen valores similares en las cuatro métricas. Lo que indica que ninguno modelo es eficaz.

## Sugerencias
* Es posible que estos modelos no sean los más adecuados para el problema. Podría probar con modelos más complejos.
* Podria revisa si hay características que puedan mejorar la predicción o si los datos están correctamente etiquetados y preparados para el modelado.
