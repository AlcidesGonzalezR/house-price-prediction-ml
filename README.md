# house-price-prediction-ml
End-to-end ML pipeline to predict house prices using Linear Regression, Decision Tree and Random Forest with Scikit-Learn
# 🏠 House Price Prediction — ML Pipeline with Scikit-Learn

> End-to-end machine learning project to predict residential property prices using Python and Scikit-Learn.

![Python](https://img.shields.io/badge/Python-3.14-blue?style=flat&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat&logo=scikit-learn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-150458?style=flat&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat)

---

## 📋 Descripción

Proyecto desarrollado como parte del portafolio de **Business Analytics & Data Science** en la University of the People.

Se construyó un pipeline completo de Machine Learning para predecir el precio de viviendas a partir de características físicas del inmueble, comparando tres algoritmos de regresión.

---

## 🎯 Resultados

| Modelo | R² | MAE | MSE |
|---|---|---|---|
| **Random Forest** ✅ | **mejor** | **menor** | **menor** |
| Decision Tree | medio | medio | medio |
| Regresión Lineal | 0.2920 | $181,510 | 74,224,655,277 |

> **sqft_living** identificada como la variable más predictiva del precio.

---

## 🔄 Pipeline del proyecto

```
Carga de datos → EDA → Limpieza → Feature Selection → Train/Test Split
       → Regresión Lineal → Decision Tree → Random Forest
              → Evaluación MSE / R² / MAE → Análisis de Residuos
```

---

## 📊 Visualizaciones incluidas

- Distribución del precio (original y log-transformada)
- Mapa de correlaciones (heatmap)
- Scatter plots: precio vs cada característica
- Comparación de métricas entre los 3 modelos
- Gráfico Real vs Predicho + distribución de residuos
- Importancia de variables (Random Forest)

---

## 🗂️ Estructura del repositorio

```
house-price-prediction-ml/
│
├── Prediccion_Precios_Vivienda_Portfolio.ipynb   # Notebook completo
├── reporte_prediccion_precios.pdf                # Reporte profesional
├── house_prices.csv                              # Dataset (4,140 registros)
└── README.md
```

---

## 🛠️ Tecnologías

| Herramienta | Uso |
|---|---|
| Python 3.14 | Lenguaje principal |
| pandas | Carga, limpieza y EDA |
| scikit-learn | Modelos ML y métricas |
| matplotlib / seaborn | Visualizaciones |
| Jupyter Notebook | Entorno de desarrollo |

---

## 🚀 Cómo ejecutar

```bash
# 1. Clonar el repositorio
git clone https://github.com/AlcidesGonzalezR/house-price-prediction-ml.git
cd house-price-prediction-ml

# 2. Instalar dependencias
pip install pandas scikit-learn matplotlib seaborn jupyter

# 3. Abrir el notebook
jupyter notebook Prediccion_Precios_Vivienda_Portfolio.ipynb
```

---

## 👤 Autor

**Alcides González**  
Especialista en Business Intelligence | 25+ años en Banca y Energía  
📍 Asunción, Paraguay

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/alcides-gonzález)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-100000?style=flat&logo=github&logoColor=white)](https://github.com/AlcidesGonzalezR)
[![Credly](https://img.shields.io/badge/Credly-Certifications-FF6B00?style=flat&logo=credly&logoColor=white)](https://www.credly.com/users/orlando-alcides-gonzalez-rodriguez)

---

*"Transformando datos en decisiones estratégicas"*
