# Machine Learning
# Portafolio de Proyectos de Machine Learning

Este repositorio contiene una colección de proyectos de Machine Learning desarrollados como parte de mi portafolio en Ciencia de Datos. Cada proyecto aborda un problema específico y utiliza diversas herramientas y técnicas de análisis y aprendizaje automático.

## Contenido

1. [Proyecto 1: Optimizacion de datos y analisis exploratorio](#proyecto-1)
2. [Proyecto 2: Analisis Avanzado y clustering de datos de clientes](#proyecto-2)
3. [Proyecto 3: Modelo de Regresión para Predicción](#proyecto-3)

---

# Proyecto 1: Limpieza y Análisis Exploratorio de Datos para Amazoff

**Descripción:**  
En este proyecto se realizó un análisis exhaustivo de un conjunto de datos proporcionado por la empresa ficticia Amazoff. El objetivo principal fue limpiar y transformar los datos en un formato adecuado para análisis futuros, además de generar visualizaciones y estadísticas útiles para la toma de decisiones de negocio.

---

## **Bibliotecas utilizadas:**
- `pandas`: Manipulación y análisis de datos.
- `numpy`: Operaciones matemáticas avanzadas y manejo de matrices.
- `matplotlib` y `seaborn`: Creación de gráficos informativos y visualización de patrones.
- `scikit-learn`: Escalamiento de datos y análisis de componentes principales (PCA).

---

## **Pasos clave realizados:**

1. **Limpieza de Datos:**
   - Identificación y manejo de valores faltantes.
   - Eliminación de datos duplicados.
   - Normalización y estandarización de datos para variables numéricas.
   - Conversión de fechas a formatos estandarizados y cálculo de diferencias de tiempo.

2. **Generación de Nuevas Variables:**
   - Creación de columnas derivadas, como tasas de precio/envío y variables de tiempo relacionadas con las fechas de compra y entrega.

3. **Visualización de Datos:**
   - Se crearon gráficos informativos para el equipo de marketing, como distribuciones de precios y patrones en las tasas de entrega.

4. **Estadísticas Generadas:**
   - Cálculo de tiempos promedio entre etapas del proceso de compra.
   - Identificación de categorías más populares y precios promedio.
   - Análisis de correlación entre variables clave.

5. **Reducción de Dimensionalidad:**
   - Implementación de PCA para visualizar los datos en un espacio reducido de dos componentes principales.
   - Visualización de los resultados del PCA en un gráfico de dispersión para identificar patrones entre los grupos de datos.

---

## **Resultados principales:**

- **Calidad de los datos:** Se redujeron los datos a un conjunto limpio de 945 filas, eliminando valores faltantes y duplicados.
- **Gráficos generados:** Tres visualizaciones clave ayudaron a identificar patrones en los datos, incluyendo:
  1. Distribución de precios y tasas de envío.
  2. Tiempos promedio entre compra y entrega.
  3. Gráficos de componentes principales que revelan tendencias y agrupaciones en los datos.
- **Estadísticas:** Se identificaron las categorías más populares y se generaron insights clave para mejorar la experiencia de los clientes.

---

## **Cómo ejecutar el notebook:**

1. Clona el repositorio:
   ```bash
   git clone https://github.com/NicLey/Data-Science-Portafolio-.git


# Proyecto 2: Analisis Avanzado y clustering de datos de clientes

**Descripción:**  
En este proyecto se llevó a cabo un análisis avanzado del comportamiento de los clientes de la empresa ficticia Amazoff. El objetivo principal fue identificar patrones en los datos y realizar una segmentación efectiva utilizando técnicas estadísticas y de machine learning. Esto permitió generar insights clave para estrategias de marketing personalizadas.

---

## **Bibliotecas utilizadas:**
- `pandas`: Para la manipulación y análisis de datos tabulares.
- `numpy`: Para cálculos numéricos y manejo de matrices.
- `matplotlib` y `seaborn`: Para la visualización de datos y creación de gráficos.
- `scikit-learn`: Para la implementación de técnicas de clustering como K-Means.

---

## **Pasos clave realizados:**

1. **Exploración de Datos:**
   - Se analizaron las variables más importantes para identificar correlaciones y patrones.
   - Se visualizaron las distribuciones y relaciones entre características.

2. **Preprocesamiento:**
   - Limpieza de datos, eliminación de valores atípicos y normalización de las características relevantes.
   - Conversión de variables categóricas a formatos adecuados para análisis.

3. **Segmentación de Clientes:**
   - Aplicación del algoritmo de clustering K-Means para agrupar clientes en segmentos basados en su comportamiento y características clave.
   - Validación de los grupos generados mediante el coeficiente silhouette.

4. **Resultados Visuales:**
   - Se generaron gráficos de dispersión para ilustrar la separación de los clusters.
   - Análisis descriptivo de cada segmento identificado.

---

## **Resultados principales:**

- **Segmentación:** Se identificaron X segmentos de clientes con características y comportamientos distintos, lo que facilita estrategias de marketing dirigidas.
- **Patrones destacados:** 
  - Segmento 1: Clientes con alto gasto y baja frecuencia.
  - Segmento 2: Clientes frecuentes pero con compras de bajo valor.
- **Visualización:** Se generaron gráficos que muestran claramente la segmentación lograda y las características clave de cada grupo.

---

## **Cómo ejecutar el notebook:**

1. Clona el repositorio:
   ```bash
   git clone https://github.com/NicLey/Data-Science-Portafolio-.git

# Proyecto 3: Optimización y Análisis Predictivo para Amazoff

**Descripción:**  
Este proyecto se centra en la construcción de modelos predictivos para identificar patrones clave en los datos de Amazoff. Se implementaron técnicas de machine learning para optimizar la precisión de las predicciones y generar insights accionables. El análisis incluyó limpieza de datos avanzada, ingeniería de características y evaluación de múltiples modelos.

---

## **Bibliotecas utilizadas:**
- `pandas`: Manipulación y análisis de datos estructurados.
- `numpy`: Cálculos numéricos avanzados.
- `matplotlib` y `seaborn`: Visualización de datos y patrones.
- `scikit-learn`: Implementación de algoritmos de machine learning para clasificación y regresión.
- `xgboost`: Entrenamiento de modelos de boosting para mejorar la precisión predictiva.

---

## **Pasos clave realizados:**

1. **Preparación de Datos:**
   - Limpieza de valores faltantes y datos atípicos.
   - Codificación de variables categóricas.
   - Normalización y estandarización de características numéricas.

2. **Ingeniería de Características:**
   - Creación de nuevas variables a partir de las existentes.
   - Análisis de importancia de características utilizando algoritmos de selección.

3. **Entrenamiento de Modelos:**
   - Evaluación de múltiples algoritmos, incluyendo regresión lineal, árboles de decisión y XGBoost.
   - Ajuste de hiperparámetros para maximizar el rendimiento del modelo.

4. **Evaluación del Modelo:**
   - Utilización de métricas como precisión, recall, F1 y ROC-AUC.
   - Comparación entre modelos para seleccionar el mejor basado en las necesidades del negocio.

---

## **Resultados principales:**

- **Modelo seleccionado:** XGBoost obtuvo una precisión del **74%** y un AUC del **87%**, superando a otros modelos probados.
- **Insights clave:**
  - Identificación de clientes con mayor probabilidad de realizar compras repetidas.
- **Visualizaciones:** Se generaron gráficos explicativos para los resultados, incluyendo:
  1. Curvas ROC para comparar modelos.
  2. Importancia de características en el modelo final.

---

## **Cómo ejecutar el notebook:**

1. Clona el repositorio:
   ```bash
   git clone https://github.com/NicLey/Data-Science-Portafolio-.git


