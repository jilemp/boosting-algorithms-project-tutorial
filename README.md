
# 🚀 Boosting Algorithms on Diabetes Dataset

This project explores the use of **Boosting and Tree-based Machine Learning algorithms** to predict diabetes outcomes based on patient data. It is an educational example for understanding model training, feature evaluation, and boosting techniques using `scikit-learn`.

## 📘 Project Goals

- Load and explore the diabetes dataset
- Preprocess and scale the data
- Train and evaluate different classification models, including:
  - `DecisionTreeClassifier`
  - `RandomForestClassifier`
  - `AdaBoostClassifier`
  - `LogisticRegression`
- Use `GridSearchCV` and cross-validation to tune models

## 🗂️ Dataset

Source: [4GeeksAcademy Diabetes Dataset](https://raw.githubusercontent.com/4GeeksAcademy/decision-tree-project-tutorial/main/diabetes.csv)

The dataset includes features like:
- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`
- `Outcome` (Target Variable)

## 🧰 Technologies Used

- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `scikit-learn` – Machine learning models and preprocessing
- `statsmodels` – Variance Inflation Factor analysis

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/jilemp/boosting-algorithms-on-diabetes-dataset.git
   ```
2. Navigate into the project folder:
   ```bash
   cd your-repo-name
   ```
3. Launch the Jupyter notebook:
   ```bash
   jupyter notebook "boosting-algorithms-project-tutorial.ipynb"
   ```

## 📈 Results

- Model performance is compared using classification metrics like **precision**, **recall**, and **f1-score**.
- Cross-validation is applied with **K-Fold** and **Repeated Stratified K-Fold** for more robust evaluation.

## 🔭 Future Work

- Explore additional boosting methods like **Gradient Boosting** or **XGBoost**
- Handle class imbalance if necessary
- Add feature importance plots and confusion matrix visualizations

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

> Created using Jupyter & Scikit-learn
