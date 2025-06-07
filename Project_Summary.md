# 💤 SleepWell: Predicting Sleep Disorders Using Machine Learning

## SDG Focus: Good Health and Well-being (SDG 3)

SleepWell uses machine learning to predict sleep disorders — specifically **Insomnia** and **Sleep Apnea** — based on individual lifestyle and health factors. By identifying at-risk individuals early, we support SDG 3 through **prevention and awareness** of sleep-related health issues.

---

## Dataset Overview

- **Source**: Kaggle – Sleep Health and Lifestyle Dataset
- **Records**: 374 individuals
- **Features**: Age, Gender, BMI, Stress Level, Sleep Duration, Physical Activity, Blood Pressure, Occupation, etc.
- **Target**: Sleep Disorder (None, Insomnia, Sleep Apnea)

---

## ML Approach

- **Type**: Supervised Classification
- **Model Used**: Random Forest Classifier
- **Preprocessing**:
  - Label Encoding for categorical variables
  - StandardScaler for normalization
  - Train/test split with stratification
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 📈 Key Results

- **Accuracy**: 84%
- **Confusion Matrix**:
  - Insomnia correctly predicted: 12/14 (86%)
  - Sleep Apnea correctly predicted: 14/17 (82%)
- **Top Features**: Stress Level, Sleep Duration, BMI Category

---

## Insights & Interpretation

- Individuals with **high stress**, **abnormal sleep duration**, or **higher BMI** are more likely to be flagged with a disorder.
- There’s overlap between **Insomnia** and **Sleep Apnea** predictions, suggesting more distinctive features (like snoring, oxygen levels) would improve detection.
- The **dataset is imbalanced**, especially for Sleep Apnea, which may limit generalization.

---

## Ethical Reflection

- **Bias Risk**: Limited data and imbalanced classes may affect fairness.
- **Use Case**: This tool is for awareness and education only — not for diagnosis.
- **Next Steps**: Use oversampling, feature expansion (e.g., wearable device data), and explore fairness metrics.

---

## Acknowledgments

- Dataset by: UOM190346A (Kaggle)
- Inspired by the UN Sustainable Development Goals (SDG 3)

