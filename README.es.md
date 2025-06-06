
# 🚀 Algoritmos de Boosting en el Conjunto de Datos de Diabetes

Este proyecto explora el uso de **algoritmos de Boosting y modelos de árboles de decisión** para predecir resultados de diabetes basados en datos clínicos. Es un ejemplo educativo para comprender el entrenamiento de modelos, evaluación de características y técnicas de boosting con `scikit-learn`.

## 📘 Objetivos del Proyecto

- Cargar y explorar el conjunto de datos de diabetes
- Preprocesar y escalar los datos
- Entrenar y evaluar diferentes modelos de clasificación, incluyendo:
  - `DecisionTreeClassifier`
  - `RandomForestClassifier`
  - `AdaBoostClassifier`
  - `LogisticRegression`
- Usar `GridSearchCV` y validación cruzada para optimizar los modelos

## 🗂️ Conjunto de Datos

Fuente: [4GeeksAcademy Diabetes Dataset](https://raw.githubusercontent.com/4GeeksAcademy/decision-tree-project-tutorial/main/diabetes.csv)

El conjunto de datos incluye variables como:
- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`
- `Outcome` (Variable Objetivo)

## 🧰 Tecnologías Utilizadas

- `pandas`, `numpy` – Manipulación de datos
- `matplotlib`, `seaborn` – Visualización
- `scikit-learn` – Modelos de aprendizaje automático y preprocesamiento
- `statsmodels` – Análisis del Factor de Inflación de Varianza (VIF)

## 🧪 Cómo Ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/jilemp/boosting-algorithms-on-diabetes-dataset.git
   ```
2. Entra en la carpeta del proyecto:
   ```bash
   cd tu-repo
   ```
3. Abre el Jupyter Notebook:
   ```bash
   jupyter notebook "boosting-algorithms-project-tutorial.ipynb"
   ```

## 📈 Resultados

- El rendimiento de los modelos se compara usando métricas como **precisión**, **recall** y **f1-score**.
- Se aplica validación cruzada usando **K-Fold** y **Repeated Stratified K-Fold** para obtener una evaluación más robusta.

## 🔭 Trabajo Futuro

- Explorar métodos de boosting adicionales como **Gradient Boosting** o **XGBoost**
- Manejar el desbalanceo de clases si es necesario
- Agregar gráficos de importancia de variables y matrices de confusión

## 📜 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

---

> Creado usando Jupyter y Scikit-learn
