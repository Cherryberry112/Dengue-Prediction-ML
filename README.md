
# 🩸 Predicting Dengue Using Blood Test Results

This repository contains an Artificial Intelligence project that leverages routine blood test data to detect Dengue fever early. By analyzing clinical parameters like Platelet count, WBC, and Hematocrit, the system provides a fast and cost-effective screening tool for medical environments.

###  Dataset Information

The data used in this project was sourced from **Kaggle**. It consists of clinical records of patients showing symptoms of dengue, focusing on hematological markers.

* **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/owmexiaolin/dengue-prediction) 
* **Key Features:** Platelets, Hemoglobin, Hematocrit, WBC, RBC, etc.

### 🚀 Key Features

* **Multi-Model Comparison**: Evaluated **XGBoost, Decision Tree, Random Forest, SVM, Logistic Regression, and Naive Bayes**.
* **Performance Leaders**: Achieved the highest predictive accuracy using **XGBoost** and **Decision Trees**.
* **Pre-processing Pipeline**: Includes handling missing values, feature selection based on clinical relevance, and data scaling.
* **Evaluation Metrics**: Models were rigorously tested using Precision-Recall curves, F1-Score, and ROC AUC analysis.

### 📂 Repository Structure

* **`Project_CSE366.ipynb`**: Jupyter Notebook containing the Kaggle data import, EDA, and model implementation.
* **`Group_1_Report_CSE366.pdf`**: Detailed academic report covering the methodology and statistical findings.

### 🛠️ Technical Stack

* **Language**: Python
* **Libraries**: `scikit-learn`, `XGBoost`, `Pandas`, `NumPy`, `Seaborn`.

### ⚙️ How to Run

1. Clone this repository.
2. Install dependencies: `pip install pandas scikit-learn xgboost seaborn`.
3. Open `Project_CSE366.ipynb`.
4. Ensure you have the dataset from the Kaggle link above (or use the one provided in the code) and run all cells.

---

### 🎓 Academic Context

* **Course**: Artificial Intelligence (CSE366)
* **Institution**: East West University
* **Team Members**: Atkiya Maisha, Mohua Akter, Asiful Alam Sami
