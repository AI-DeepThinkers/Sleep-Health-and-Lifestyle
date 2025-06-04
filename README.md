# 💤 SleepWell: Predicting Sleep Disorders Using ML

## 🧭 Overview

SleepWell is a machine learning project designed to predict **sleep disorders** (Insomnia, Sleep Apnea) using health and lifestyle indicators. It aligns with **Sustainable Development Goal (SDG) 3 – Good Health and Well-being** by promoting early detection and awareness of sleep-related issues.

---

## 📌 SDG Alignment: SDG 3 – Good Health and Well-being

Sleep is vital to both physical and mental health. This project uses data-driven approaches to:
- Encourage better sleep hygiene
- Identify individuals at risk for common sleep disorders
- Promote early lifestyle intervention

---

## 📊 Dataset

- **Source:** [Kaggle - Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)
- **Records:** 374 individuals
- **Features:** Age, Gender, BMI, Stress Level, Sleep Duration, Physical Activity, Blood Pressure, Occupation, etc.

---

## ⚙️ Setup Instructions

> 🔹 Recommended: Use a virtual environment (venv or conda)

### 1. Clone the Repository

```bash

```

### 2. Create and Activate Virtual Environment
Windows:

```bash
python -m venv venv
venv\Scripts\activate
```
macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```
### 3. Install Requirements
```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```


### How to Run the Notebook
```bash
jupyter notebook
```
Then open sleepwell_prediction.ipynb and run the cells step-by-step.

### 🧠 Machine Learning Approach
Model: Random Forest Classifier

Target: Sleep Disorder

Features Used: Age, Sleep Duration, BMI Category, Stress, etc.

Evaluation: Accuracy, Confusion Matrix, Feature Importance

### 📈 Sample Outputs
- Count plots showing distribution of sleep disorders
- Correlation heatmap of lifestyle factors
- Classification metrics (accuracy, F1-score)
- Feature importance ranking

### ⚖️ Ethical Considerations
- Bias: Lifestyle factors differ across cultures and should not be overgeneralized.
- Fairness: Categorical data encoded carefully to avoid discrimination.
- Use Case: This model is for awareness only, not for medical diagnosis.
  
### 🙌 Acknowledgments
- Dataset by: UOM190346A on Kaggle
- Inspired by the use of AI for good under the UN SDG framework.
