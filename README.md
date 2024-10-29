# Trabajo Práctico N° 2 - Minería de Datos

**Año:** 2024  
**Materia:** Minería de Datos  

## Objetivo

El objetivo de este trabajo práctico es aplicar los conocimientos de minería de datos adquiridos en las unidades 4 y 5, resolviendo dos problemas: uno sobre el comportamiento financiero de empresas y otro en un juego de cartas. A través de estos problemas, se exploran técnicas de estandarización, árboles de decisión, Bayes ingenuo y k-vecinos más cercanos (k-NN).

## Actividades

1. **Análisis de Datos de Compañías:**
   - Descargar el dataset `1000_Companies.csv`.
   - Realizar análisis de los atributos (distribuciones, valores, outliers, tipos de datos, etc.).
   

2. **Predicción de Beneficios (Profit) con Árboles de Decisión:**
   - Aplicar árboles de decisión de regresión para estimar el atributo **Profit**.
   - Evaluar parámetros como profundidad máxima, número mínimo de observaciones, y criterio de separación.
   - Graficar el árbol obtenido y analizar su rendimiento sobre dos conjuntos de test mediante las métricas:
     - Error Absoluto Medio (MAE)
     - Error Cuadrático Medio (MSE)
     - Raíz del Error Cuadrático Medio (RMSE)

3. **Análisis de Datos de Pokémon:**
   - Descargar el dataset `PokemonDBCart.csv`.
   - Realizar un análisis de atributos similar al paso 1.
   - Crear dos conjuntos de datos para entrenar y evaluar los modelos: 80-20 y 70-30.

4. **Clasificación de Tipo de Pokémon con Árboles de Decisión:**
   - Aplicar árboles de decisión para clasificar el **Tipo de Pokémon**.
   - Analizar el impacto de la profundidad máxima, número mínimo de observaciones, y criterio de separación.
   - Graficar el árbol de decisión, realizar una poda y evaluar el rendimiento en ambos conjuntos de test con las métricas:
     - Precisión
     - Exhaustividad (Recall)
     - Exactitud (Accuracy)

5. **Clasificación de Tipo de Pokémon con Bayes Ingenuo:**
   - Implementar el modelo de Bayes ingenuo para clasificar el **Tipo de Pokémon**.
   - Discretizar atributos según un criterio elegido.
   - Evaluar los resultados sobre ambos conjuntos de test utilizando las mismas métricas.

6. **Clasificación de Tipo de Pokémon con k-Vecinos Más Cercanos (k-NN):**
   - Implementar el modelo k-NN para estimar el **Tipo de Pokémon**.
   - Analizar parámetros como número de vecinos, métrica de distancia, y valor de `p`.
   - Evaluar el modelo en ambos conjuntos de test con las métricas de evaluación.

## Resultados y Conclusiones

- Cada actividad está documentada con gráficos e interpretaciones sobre la validez de los resultados y la coherencia con las hipótesis previas.
- Para resultados detallados, revisar cada sección en el archivo `.ipynb` donde se explican los parámetros ajustados y la interpretación de las métricas obtenidas en los modelos aplicados.
