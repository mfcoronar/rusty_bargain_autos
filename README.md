# 🚗 Rusty Bargain - Predicción del Valor de Mercado de Autos Usados

Este proyecto busca desarrollar un modelo de *Machine Learning* que prediga con precisión el **valor de mercado de autos usados**, con base en las características del vehículo. La iniciativa forma parte de un caso empresarial ficticio de **Rusty Bargain**, una empresa que compra y revende autos usados a precios competitivos.

## 📍 Contexto

Rusty Bargain desea automatizar y mejorar su proceso de fijación de precios al adquirir vehículos, para así optimizar su margen de ganancia. Para lograrlo, se nos ha encomendado construir un modelo predictivo que considere:

- **Calidad de la predicción**
- **Velocidad de predicción**
- **Tiempo de entrenamiento**

## 🎯 Objetivo

Construir un modelo de regresión que estime el **precio de reventa** de un automóvil usado con base en sus características técnicas e históricas, manteniendo un equilibrio entre precisión y eficiencia computacional.

## 🧾 Dataset

El conjunto de datos incluye variables como:
- Marca y modelo
- Año de fabricación
- Potencia del motor
- Tipo de combustible
- Kilometraje
- Transmisión
- Tipo de vehículo
- Fecha de registro
- Precio de venta (variable objetivo)

## 🛠️ Herramientas utilizadas

- Python
  - pandas, NumPy
  - scikit-learn
  - LightGBM, CatBoost, XGBoost
  - Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Etapas del proyecto

1. **Exploración y limpieza de datos**  
   - Eliminación de valores atípicos y nulos
   - Conversión de tipos de datos
   - Codificación de variables categóricas

2. **Análisis exploratorio**  
   - Correlaciones entre características y el precio
   - Visualización de distribuciones y relaciones clave

3. **Entrenamiento de modelos**  
   - Regresión lineal
   - Árboles de decisión
   - LightGBM, CatBoost, XGBoost

4. **Evaluación del modelo**  
   - Métrica principal: RMSE
   - Comparación de velocidad y precisión entre modelos

5. **Selección del modelo final**  
   - Basado en rendimiento en el conjunto de prueba y tiempo de inferencia

## ✅ Resultados

- El modelo seleccionado alcanzó un **RMSE competitivo** en el conjunto de prueba.
- Se logró una **buena velocidad de predicción** y un **tiempo de entrenamiento razonable**, alineado con los requerimientos del negocio.
- Las variables más influyentes en el precio fueron: año del coche, kilometraje, potencia del motor y marca.
