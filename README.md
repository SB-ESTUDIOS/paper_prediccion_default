# paper_prediccion_default

Los SHAP values son una herramienta poderosa para comprender cómo contribuyen las variables a la probabilidad de caer en default
en un modelo de riesgo. Este documento proporciona una guía sobre cómo interpretar los SHAP values en el excel.


¿Qué son los SHAP Values?
Los SHAP (SHapley Additive exPlanations) values son una técnica de explicación de modelos que descompone la predicción de un 
modelo en la contribución de cada variable. En el contexto de los modelos de riesgo de default, los SHAP values nos permiten 
entender cómo cada variable afecta la probabilidad de que un individuo o entidad caiga en default.


Interpretación de los SHAP Values
Cuando analizamos los SHAP values para una variable específica, estamos evaluando su impacto promedio en la probabilidad de 
default para cada categoría de esa variable. Es importante tener en cuenta que solo tiene sentido al considerar una 
variable a la vez.

Por ejemplo, si estamos analizando el SHAP value de la variable "ingresos", podemos observar cuánto contribuyen 
diferentes niveles de ingresos a la probabilidad de default. 
