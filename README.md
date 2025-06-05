
# 🍷 K-Nearest Neighbors (KNN) Classification – Wine Dataset

## 📌 Objective
Implement and evaluate the K-Nearest Neighbors (KNN) classification algorithm on the Wine dataset to distinguish between three types of wine based on chemical analysis.

---

## 🧰 Tools Used
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib**

---

## 📊 Dataset Description

The Wine dataset is a classic multiclass classification dataset. It contains 178 samples of wine with 13 numerical features such as:
- Alcohol
- Malic acid
- Ash
- Alcalinity of ash
- Magnesium
- Flavanoids
- Proline

The target variable indicates the wine class (three cultivars).

---

## 🧭 Steps Followed

### 1. **Load and Explore Dataset**
- Loaded using `load_wine()` from `sklearn.datasets`
- Displayed feature names and classes

### 2. **Normalize Features**
- Applied `StandardScaler` for feature scaling

### 3. **Split Data**
- Used `train_test_split()` to divide data into training and test sets

### 4. **Train and Evaluate KNN**
- Trained `KNeighborsClassifier` using K values from 1 to 10
- Plotted accuracy for each K

### 5. **Evaluate Best Model**
- Selected best K based on highest accuracy
- Displayed confusion matrix for detailed performance analysis

---

## ✅ Observations

- KNN performs well on the wine dataset after scaling features
- Confusion matrix helps understand classification performance across all classes

---

## 🔗 Reference
- [Scikit-learn Wine Dataset Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html)
