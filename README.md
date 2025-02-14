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

## Las métricas utilizadas para evaluar los modelos fueron: MSE, RMSE, MAE y R².

|Modelo|	MSE|	R²|	RMSE|	MAE|
|:-----|:-----|:-----|:-----|:-----|
|Árbol de Decisión|	1516.11|	0.0003|	38.93|	33.66|
|Gradient Boosting|	1514.82|	0.0011|	38.92|	33.64|
|CatBoostRegressor|	1515.05|	0.0010|	38.92|	33.65|
