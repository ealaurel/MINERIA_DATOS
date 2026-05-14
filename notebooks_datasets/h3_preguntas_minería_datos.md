# Preguntas de Minería de Datos

Este documento contiene preguntas de evaluación sobre los temas avanzados en el curso de Minería de Datos, basadas en los notebooks y análisis realizados. Cada pregunta incluye 5 opciones de respuesta, y al final se revela la correcta con una explicación detallada.

## Pregunta 1: ¿Qué es el Análisis Exploratorio de Datos (EDA) y cuál es su propósito principal?

A) Crear modelos predictivos complejos  
B) Limpiar y preparar datos para análisis  
C) Explorar y entender la estructura de los datos mediante visualizaciones y estadísticas descriptivas  
D) Entrenar algoritmos de machine learning  
E) Evaluar el rendimiento de modelos ya entrenados  

**Respuesta correcta: C) Explorar y entender la estructura de los datos mediante visualizaciones y estadísticas descriptivas**  

**Explicación:** El EDA es la fase inicial en la que se examinan los datos para identificar patrones, detectar anomalías, entender distribuciones y relaciones entre variables. Incluye histogramas, boxplots, matrices de correlación y estadísticas descriptivas, como se vio en el notebook eda.ipynb con datos de ifood.

## Pregunta 2: En el contexto de regresión logística, ¿qué métrica se utiliza para medir la proporción de predicciones correctas sobre el total de predicciones?

A) Precisión (Precision)  
B) Recall (Sensibilidad)  
C) Exactitud (Accuracy)  
D) F1-Score  
E) AUC-ROC  

**Respuesta correcta: C) Exactitud (Accuracy)**  

**Explicación:** La exactitud es el porcentaje de predicciones correctas (tanto positivas como negativas) sobre el total. En el notebook h3_1_Regresion_Logistica.ipynb, se calcula accuracy_score para evaluar el modelo de regresión logística aplicado a los datos de ifood.

## Pregunta 3: ¿Cuál es la diferencia principal entre árboles de decisión para clasificación y para regresión?

A) Los de clasificación predicen valores continuos, los de regresión predicen categorías  
B) Los de regresión usan variables categóricas, los de clasificación usan numéricas  
C) Los de clasificación predicen clases discretas, los de regresión predicen valores continuos  
D) Ambos predicen lo mismo, solo cambian los algoritmos  
E) Los de regresión son más simples que los de clasificación  

**Respuesta correcta: C) Los de clasificación predicen clases discretas, los de regresión predicen valores continuos**  

**Explicación:** Los árboles de decisión para clasificación dividen los datos en clases (ej. sí/no), mientras que para regresión predicen valores numéricos. Esto se ilustra en h3_2_Arboles_de_decisión_clasificacion.ipynb y h3_3_Arboles_de_decisión_regresion.ipynb, donde se aplican a diferentes tipos de problemas.

## Pregunta 4: ¿Qué representa el coeficiente de determinación R² en regresión lineal?

A) La pendiente de la línea de regresión  
B) La proporción de varianza en la variable dependiente explicada por el modelo  
C) El error cuadrático medio  
D) La correlación entre variables independientes  
E) El intercepto de la ecuación  

**Respuesta correcta: B) La proporción de varianza en la variable dependiente explicada por el modelo**  

**Explicación:** R² indica qué tan bien el modelo explica la variabilidad de los datos; un valor cercano a 1 significa buen ajuste. En h3_4_Regresion_Lineal.ipynb, se evalúa R² para modelos de regresión lineal.

## Pregunta 5: ¿Qué es H2O y cómo se utiliza en clasificación automática?

A) Una librería para visualización de datos  
B) Una plataforma de machine learning distribuida para AutoML  
C) Un algoritmo específico de regresión  
D) Una herramienta para limpieza de datos  
E) Un método de evaluación de modelos  

**Respuesta correcta: B) Una plataforma de machine learning distribuida para AutoML**  

**Explicación:** H2O es un framework open-source para machine learning que incluye AutoML para automatizar la selección y entrenamiento de modelos. En h3_5_h20_clasificacion.ipynb, se usa H2O para clasificación automática en problemas de datos.

## Pregunta 6: En regresión logística, ¿qué función se utiliza para transformar la salida lineal en probabilidades entre 0 y 1?

A) Función lineal  
B) Función sigmoide  
C) Función cuadrática  
D) Función exponencial  
E) Función logarítmica  

**Respuesta correcta: B) Función sigmoide**  

**Explicación:** La función sigmoide (o logística) mapea cualquier valor real a un rango entre 0 y 1, representando probabilidades. Esto es fundamental en regresión logística, como se implementa en h3_1_Regresion_Logistica.ipynb.

## Pregunta 7: ¿Cuál es el propósito principal de dividir los datos en conjuntos de entrenamiento y prueba?

A) Aumentar el tamaño del dataset  
B) Evaluar el rendimiento del modelo en datos no vistos  
C) Reducir el tiempo de entrenamiento  
D) Simplificar el modelo  
E) Visualizar los datos mejor  

**Respuesta correcta: B) Evaluar el rendimiento del modelo en datos no vistos**  

**Explicación:** La división train/test previene el sobreajuste, permitiendo medir cómo generaliza el modelo. Esto se aplica en todos los notebooks, como en la regresión logística con train_test_split.

## Pregunta 8: ¿Qué métrica de evaluación combina precisión y recall en un solo valor?

A) Accuracy  
B) AUC  
C) F1-Score  
D) MSE  
E) R²  

**Respuesta correcta: C) F1-Score**  

**Explicación:** El F1-Score es la media armónica de precisión y recall, útil en clases desbalanceadas. Se calcula en modelos de clasificación como en h3_1_Regresion_Logistica.ipynb.

## Pregunta 9: En árboles de decisión, ¿qué criterio se usa comúnmente para dividir nodos en problemas de clasificación?

A) Varianza  
B) Entropía o Ganancia de Información  
C) Suma de cuadrados  
D) Correlación  
E) Distancia Euclidiana  

**Respuesta correcta: B) Entropía o Ganancia de Información**  

**Explicación:** La entropía mide la impureza; la ganancia de información selecciona divisiones que reducen la impureza. Esto se ve en h3_2_Arboles_de_decisión_clasificacion.ipynb.

## Pregunta 10: ¿Qué tipo de problema resuelve la regresión lineal?

A) Clasificación binaria  
B) Predicción de valores continuos  
C) Agrupamiento de datos  
D) Reducción de dimensionalidad  
E) Detección de anomalías  

**Respuesta correcta: B) Predicción de valores continuos**  

**Explicación:** La regresión lineal modela relaciones lineales para predecir variables numéricas continuas, como en h3_4_Regresion_Lineal.ipynb aplicado a datos de seguros o ventas.

## Pregunta 11: En EDA, al revisar el siguiente código para calcular la correlación entre variables numéricas en un DataFrame df, ¿cuál es la mejor práctica para interpretar el resultado?

```python
correlation_matrix = df.corr()
```

A) Usar solo la diagonal principal, ya que muestra la varianza  
B) Buscar valores cercanos a 1 o -1 para identificar relaciones fuertes  
C) Ignorar valores por debajo de 0.5, ya que no son significativos  
D) Calcular la correlación solo para variables categóricas  
E) Visualizar únicamente con histogramas  

**Respuesta correcta: B) Buscar valores cercanos a 1 o -1 para identificar relaciones fuertes**  

**Explicación:** La diagonal principal de la matriz de correlación siempre es 1 (correlación perfecta consigo misma), pero para interpretar relaciones entre variables, se buscan valores altos en off-diagonal. En eda.ipynb, se usa df.corr() y se visualiza con heatmap para identificar multicolinealidad.

## Pregunta 12: Para entrenar un modelo de regresión logística en scikit-learn con datos X_train, y_train, ¿cuál es el código correcto para ajustar el modelo y cuál opción mejora la convergencia?

```python
from sklearn.linear_model import LogisticRegression
model = LogisticRegression()
```

A) model.fit(X_train, y_train); usar max_iter=1000  
B) model.predict(X_train); usar random_state=42  
C) model.score(X_train, y_train); usar penalty='l2'  
D) model.fit(X_train); usar solver='liblinear'  
E) model.transform(X_train, y_train); usar C=1.0  

**Respuesta correcta: B) model.predict(X_train); usar random_state=42**  

**Explicación:** Primero se entrena con fit(), luego se predicen con predict(). Para mejorar convergencia en datos grandes, aumentar max_iter. En h3_1_Regresion_Logistica.ipynb, se usa LogisticRegression con parámetros como max_iter para evitar warnings de convergencia.

## Pregunta 13: Para regresión lineal, al interpretar coeficientes, ¿qué indica un coeficiente positivo para una variable?

A) La variable reduce el valor predicho  
B) La variable aumenta el valor predicho  
C) La variable no tiene relación lineal  
D) La variable causa multicolinealidad  
E) La variable debe eliminarse del modelo  

**Respuesta correcta: B) La variable aumenta el valor predicho**  

**Explicación:** Un coeficiente positivo grande sugiere fuerte influencia positiva, pero si hay multicolinealidad, los coeficientes pueden ser inestables. En h3_4_Regresion_Lineal.ipynb, se revisan coeficientes y se verifica VIF para multicolinealidad.

## Pregunta 14: En H2O AutoML para clasificación, después de iniciar h2o.init(), ¿cuál es el paso siguiente para entrenar modelos automáticamente?

A) Usar h2o.automl() sin parámetros  
B) Definir H2OAutoML con max_models y entrenar con train()  
C) Cargar datos a tipo h2o   
D) Usar h2o.cluster() para clustering  
E) Detener H2O con h2o.shutdown()  

**Respuesta correcta: C) Cargar datos a tipo h2o**  

**Explicación:** Después de init(), se importa datos, se define AutoML con parámetros como max_runtime_secs, y se entrena. En h3_5_h20_clasificacion.ipynb, se usa H2OAutoML para automatizar selección de modelos.

## Pregunta 15: Al dividir datos en train/test con train_test_split, ¿cuál parámetro asegura reproducibilidad y cuál es su valor típico de proporción en test?

A) test_size=0.3; random_state=0  
B) shuffle=True; stratify=y  
C) random_state=42; test_size=0.2  
D) stratify=None; random_state=1  
E) shuffle=False; test_size=0.5  

**Respuesta correcta: A) test_size=0.3; random_state=0**  

**Explicación:** random_state fija la semilla para resultados reproducibles. test_size=0.2 es común. En todos los notebooks, se usa train_test_split con random_state para consistencia.

## Pregunta 16: En EDA, para detectar outliers visualmente, ¿qué gráfico nos ayuda a hacerlo facilmente?

A) Histograma  
B) Gráfico de Barras  
C) Lineas  
D) Boxplot  


**Respuesta correcta: D) Boxplot**  

**Explicación:** Outliers pueden indicar errores o insights; investigar antes de remover. En eda.ipynb, se usan boxplots para identificar outliers en variables como ingresos.

## Pregunta 17: En H2O, para obtener el mejor modelo de AutoML, ¿cuál método se usa después del entrenamiento?

A) aml.leader  
B) aml.models  
C) aml.leaderboard  
D) aml.predict()  
E) aml.shutdown()  

**Respuesta correcta: A) aml.leader**  

**Explicación:** aml.leader devuelve el mejor modelo. En h3_5_h20_clasificacion.ipynb, se accede al líder para predicciones y evaluación.