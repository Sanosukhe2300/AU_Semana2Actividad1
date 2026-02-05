# AU_Semana2Actividad1

# Clasificación técnica mediante SVM y Árboles de Decisión

## 📌 Descripción del problema
El objetivo de este proyecto es predecir si un usuario realizará una compra a partir de información demográfica básica obtenida de una red social. Este tipo de predicción es clave en estrategias de marketing digital, ya que permite optimizar campañas publicitarias y segmentar audiencias de forma eficiente.

## 📊 Dataset
El dataset contiene 400 registros con las siguientes variables:
- Gender (género del usuario)
- Age (edad)
- EstimatedSalary (salario estimado)
- Purchased (variable objetivo)

## ⚙️ Metodología
1. Análisis exploratorio de datos (EDA)
2. Preprocesamiento:
   - Codificación de variables categóricas
   - Escalado de características
3. División del dataset en entrenamiento y prueba
4. Entrenamiento de modelos de clasificación:
   - Regresión Logística
   - Support Vector Machine (SVM)
   - Árbol de Decisión
5. Evaluación de modelos mediante:
   - Matriz de confusión
   - Accuracy
   - Validación cruzada
6. Visualización de fronteras de decisión

## 📈 Resultados
El modelo SVM obtuvo el mejor desempeño, con una accuracy aproximada del 93% y alta estabilidad en validación cruzada.

## ✅ Conclusiones
El análisis demuestra que la edad y el salario estimado son variables clave en la decisión de compra. El modelo SVM resulta ser el más adecuado para este problema, ofreciendo una separación más precisa entre compradores y no compradores.
