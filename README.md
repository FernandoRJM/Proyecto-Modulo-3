# Modelo supervisado

## 📝 Descripción
Este proyecto tiene como objetivo diseñar y aplicar modelos de Machine Learning Supervisado para resolver dos problemas distintos utilizando un conjunto de datos de Recursos Humanos:

1. Regresión: Predecir el salario pretendido por postulantes en empresas de tecnología basándose en características como años de experiencia, posición, educación y estado civil.

2. Clasificación: Implementar modelos de regresión logística para tareas de clasificación, evaluando su desempeño mediante métricas de precisión y matrices de confusión.

## 🛠️ Herramientas y Tecnologías

• Lenguaje: Python 3.x. 
• Librerías: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn. 
• Algoritmos: * Regresión Lineal (Linear Regression). * Regresión Logística (Logistic Regression). 
• Técnicas: Ingeniería de características (Creación de dummies), Escalado de datos (StandardScaler) y Validación Cruzada (Train/Test Split).

## 📊 Dashboard / Resultados

El proyecto evaluó el desempeño mediante dos enfoques: regresión para salarios y clasificación para tipos de perfiles. Los hallazgos principales fueron:

1. Predicción de Salarios (Regresión Lineal)

• Precisión del Modelo (R2): Se obtuvo un valor de 0.46, lo que indica que el modelo explica el 46% de la variabilidad de los salarios.
• Error Medio (RMSE): El error promedio en la predicción de salarios fue de $1,735, un margen aceptable considerando la dispersión salarial en el sector tecnológico.
• Hallazgo: Los años de experiencia y el nivel educativo resultaron ser los predictores con mayor peso estadístico.

2. Clasificación de Perfiles (Regresión Logística)

• Exactitud (Accuracy): El modelo logró un 85.7% de precisión global al clasificar si un perfil pertenece a una categoría específica.
• Métricas de Detalle:
• Precisión: 0.86 (Alta capacidad para no dar falsos positivos).
• Recall (Sensibilidad): 0.86 (Alta capacidad para detectar todos los casos reales).
• Matriz de Confusión: Se observó un equilibrio sólido entre verdaderos positivos y negativos, con muy pocos errores de clasificación en el set de prueba.
