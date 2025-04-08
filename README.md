#  Ensemble Learning: Voting Classifier on Biomechanical Data

This project implements an **Ensemble Learning** model using a **Voting Classifier** to predict the class of orthopedic patients based on their biomechanical features combining : 


- **K-Nearest Neighbors (KNN)**
- **Gaussian Naive Bayes**
- **Bernoulli Naive Bayes**
- **Decision Tree**

---

## 📊 Dataset Information

- **Source**: [Biomechanical Features of Orthopedic Patients - Kaggle](https://www.kaggle.com/datasets/uciml/biomechanical-features-of-orthopedic-patients/data)
- Each sample in the dataset represents a patient with six biomechanical attributes:
  - Pelvic incidence
  - Pelvic tilt
  - Lumbar lordosis angle
  - Sacral slope
  - Pelvic radius
  - Grade of spondylolisthesis

---

## 🧰 Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for imbalanced output classes
- Pairplot visualizations for feature relationships
- Correlation matrix to assess feature relationships
- Box plots for each feature
- Distribution plots to visualize the spread of values in each column

---

## 🧼 Data Preprocessing

- Checked for missing values
- Standardized features using `StandardScaler`
- Balanced the dataset using `RandomOverSampler`
- Split the dataset into training and testing sets using `train_test_split`

---

## 🤖 Classifiers Used in Voting Ensemble

- **K-Nearest Neighbors (KNN)**
- **Gaussian Naive Bayes**
- **Bernoulli Naive Bayes**
- **Decision Tree**


---

## 📉 Testing Metrics

- **Accuracy Score**
- **Confusion Matrix**


---

## 📈 Results


| Model           | Accuracy (Train) | Accuracy (Validation) |
|----------------|------------------|------------------------|
| Decision Tree  | 0.9441           | 0.9556                 |
| Naive Bayes    | 0.9058           | 0.9315                 |
| KNN | 0.9137  | 0.9153                 |





![image](https://github.com/user-attachments/assets/bf5d9461-6d6d-4a89-a5d5-bac084490a67)
