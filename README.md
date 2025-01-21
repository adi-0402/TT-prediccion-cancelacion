---

# Predicción de Cancelación de Clientes en Interconnect

---

## 🔖 Descripción del Proyecto
Este proyecto desarrolla un modelo predictivo para identificar clientes de Interconnect, un operador de telecomunicaciones, que están en riesgo de cancelar sus servicios. Utilizando datos sobre contratos, uso de servicios y características personales, se busca optimizar las estrategias de retención al ofrecer incentivos personalizados. Este proyecto se realizo con TripleTen.

---

## 💻 Funcionalidades
- **Preprocesamiento de Datos**: Limpieza y combinación de múltiples conjuntos de datos, manejo de valores nulos y codificación de variables categóricas.
- **Análisis Exploratorio de Datos (EDA)**: Visualizaciones como histogramas y boxplots para identificar patrones en el comportamiento de los clientes.
- **Ingeniería de Características**: Creación de nuevas variables como "duración del contrato" y "cargos totales por mes".
- **Selección de Características**: Uso de Boruta y SHAP para identificar las variables más relevantes.
- **Modelado Predictivo**: Implementación de varios modelos de Machine Learning, incluyendo:
  - Logistic Regression
  - Decision Tree Classification
  - Random Forest Classifier
  - XGBoost
  - K-Nearest Neighbors (KNN)
- **Evaluación del Modelo**: Análisis basado en métricas como AUC-ROC, F1-score, precisión y recall.

---

## 🛠️ Tecnologías Utilizadas
- Python
- Pandas 
- NumPy 
- Scikit-learn 
- XGBoost
- Matplotlib
- Seaborn
- Boruta
- SHAP

---

## 🔢 Resultados
- **Mejor Modelo**: XGBoost
  - Valores destacados: F1-score de **0.84** y AUC-ROC de **0.95** en el conjunto de prueba.
- Otros modelos, como Logistic Regression y Decision Tree Classification, también mostraron desempeños competitivos, aunque inferiores a XGBoost.

---

## ✨ Conclusiones
- **Impacto del Proyecto**: 
  Este modelo predictivo permite identificar clientes en riesgo de cancelación, ayudando a Interconnect a implementar estrategias de retención proactivas como ofertas personalizadas y beneficios adicionales.
- **Segmentación de Clientes**: 
  La combinación de datos contractuales, personales y de uso permite segmentar a los clientes en grupos específicos, optimizando las acciones de retención.
- **Uso de Servicios Adicionales**: 
  Los clientes que utilizan servicios adicionales, como soporte técnico y almacenamiento en la nube, tienen una menor probabilidad de cancelación, lo que podría guiar futuras iniciativas de marketing.

---
