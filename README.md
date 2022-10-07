# Predicción de presupuesto de campañas en Meta Ads mediante Regresión Lineal

El presente notebook tiene como propósito el análisis exploratorio, descriptivo y predictivo de un conjunto de datos proveniente de campañas digitales en Facebook Ads.

## Código y recursos utilizados
* Versión de Python: 3.8
* Librerías: pandas, numpy, sklearn, matplotlib, seaborn, scipy, xgboost
* Dataset: propio, datos anonimizados de Meta Ads

## Análisis Exploratorio

Se realizó un breve Análisis Exploratorio de los datos con el objetivo de estudiar:
- Inversión acumulada por objetivo de campaña.
- Inversión acumulada mensual en el periodo bajo estudio.
- Correlación entre variables.
- Histogramas de frecuencias de variables.

## Análisis Predictivo

Se desarrolló un análisis de Regresión Lineal a través de modelos predictivos teniendo como objetivo la variable Inversión. Para tal fin, se desarrollaron cuatro modelos predictivos y se compararon sus métricas:

1) Linear Regression

2) Decision Tree Regressor

3) Support Vector Regressor

4) XGB Regressor

## Conclusiones

- De acuerdo al análisis de métricas realizado, el modelo con mejor desempeño fue Linear Regression, seguido de XGBoost, Decision Tree y SVM. Aunque los modelos se podrían mejorar con algunas acciones como: mayor cantidad de datos, optimización de hiperparámetros, ensambles, etc.

- Como se observó en gráficos precedentes, la mayoría de las variables analizadas están correlacionadas con el monto invertido en campañas digitales (clicks, alcance, impresiones, entre otros), por tanto, la prediccón de presupuestos resulta de utilidad para establecer valores de KPI a alcanzar para los objetivos de marketing.

- Para finalizar, se mencionan algunas variables de utilidad para mejorar las predicciones de inversión en campañas digitales:

*Campañas en general:*
* ROAS
* Resultados
* Costo por Resultado
* CTR
* CTA

*Campañas de conversión Ecommerce:*
* Resultados basados en la etapa del funnel
