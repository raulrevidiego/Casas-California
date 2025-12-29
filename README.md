# 🏠 California Housing – Análisis de Datos y Machine Learning

Este proyecto realiza un **análisis exploratorio de datos (EDA)** y la **construcción de modelos de Machine Learning** para predecir el **precio medio de viviendas en California**, utilizando el conocido *California Housing Dataset*.

El objetivo es comprender las relaciones entre variables socioeconómicas y geográficas, preparar los datos correctamente y aplicar modelos de regresión supervisada.

---

## 📊 Dataset

- Fuente: California Housing Dataset (derivado del censo de California)
- Tipo de problema: **Regresión**
- Variable objetivo:
  - `MedHouseVal` → Valor medio de la vivienda
- Variables principales:
  - `MedInc` → Ingreso medio
  - `HouseAge` → Edad media de las viviendas
  - `AveRooms` → Número medio de habitaciones
  - `AveBedrms` → Número medio de dormitorios
  - `Population`
  - `AveOccup` → Ocupación media
  - `Latitude`, `Longitude`

---

## 🔍 Análisis Exploratorio de Datos (EDA)

Durante el análisis exploratorio se estudiaron:

- Distribución de la variable objetivo
- Relación entre:
  - Ingresos y precio de la vivienda
  - Ubicación geográfica y valor inmobiliario
  - Densidad de población y precios
- Identificación de:
  - Distribuciones sesgadas
  - Outliers
  - Correlaciones relevantes

Se utilizaron histogramas, gráficos de dispersión y mapas de correlación para extraer patrones clave.

---

## 🧹 Limpieza y Preprocesamiento

Las principales tareas de preprocesamiento incluyen:

- Revisión de valores faltantes
- Análisis estadístico de variables numéricas
- Preparación del dataset para modelos de ML
- Separación de variables predictoras y variable objetivo

El enfoque se centra en mantener un **pipeline limpio y reproducible**, evitando fugas de información (*data leakage*).

---

## 🤖 Machine Learning

Se aplican modelos de **regresión supervisada** para predecir el valor medio de la vivienda:

- Separación train / test
- Entrenamiento de modelos
- Evaluación mediante métricas de regresión:
  - R²
  - Error cuadrático medio (MSE / RMSE)

El proyecto está preparado para comparar distintos algoritmos y mejorar el rendimiento mediante ajustes y transformaciones adicionales.

---

## 🧠 Conclusiones

Algunas conclusiones clave del análisis:

- El ingreso medio (`MedInc`) es la variable con mayor poder predictivo
- La localización geográfica tiene un impacto significativo en el precio
- Existen relaciones no lineales que pueden beneficiarse de modelos más complejos
- El preprocesamiento es crítico para obtener buenos resultados en regresión

---

## 🛠️ Tecnologías Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Posibles Mejoras Futuras

- Escalado de variables
- Ingeniería de características
- Comparación entre modelos:
  - Linear Regression
  - Ridge / Lasso
  - Random Forest
- Validación cruzada
- Optimización de hiperparámetros

---

## 👤 Autor

Proyecto realizado por **Raúl Revidiego**  
Enfocado en aprendizaje práctico, análisis riguroso de datos y buenas prácticas en Machine Learning.

---

## 📌 Nota

Este proyecto tiene fines educativos y forma parte del desarrollo de habilidades en **Ciencia de Datos y Machine Learning**.

