# Predicción de Default en RD: un enfoque de Machine Learning para la evaluación del riesgo crediticio

Este repositorio aloja los SHAP values presentados en la investigación _Predicción de Default en RD: un enfoque de Machine
Learning para la evaluación del riesgo crediticio_, la cual se puede encontrar [aquí](https://sb.gob.do/publicaciones/publicaciones-tecnicas/prediccion-de-default-en-rd-un-enfoque-de-machine-learning-para-la-evaluacion-del-riesgo-crediticio/).
Los SHAP values constituyen una herramienta poderosa para comprender cómo contribuyen las variables a la probabilidad de caer en default
en un modelo de riesgo. A continuación se describe brevemente qué son los SHAP values y cómo se deben interpretar.


## ¿Qué son los SHAP Values?
A través de los SHAP (SHapley Additive exPlanations) values se puede cuantificar la contribución de cada variable en un modelo a la predicción final. En el contexto de los modelos de riesgo de default, los SHAP values nos permiten 
entender cómo cada variable afecta la probabilidad de que un individuo caiga en default.


## Interpretación de los SHAP Values
Cuando analizamos los SHAP values para una variable específica, estamos evaluando su impacto promedio en la probabilidad de 
default para cada categoría de esa variable. Es importante tener en cuenta que solo tiene sentido al considerar una 
variable a la vez.

Por ejemplo, si estamos analizando el SHAP value de la variable "ingresos", podemos observar cuánto contribuyen 
diferentes niveles de ingresos a la probabilidad de default. 
