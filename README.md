# Project Pyhton - Machine Learning: 🧬SVM - based Cancer Cell Classification🧬

---
## 🔥 Casestudy

You are given a dataset consisting of records containing information about human body cells. You will use SVM (Support Vector Machines) to build and train a model to classify cells to determine whether samples are benign or malignant.

--- 

## 📌 Project Objective  
This project utilizes Support Vector Machines (SVM) to build a model that classifies human body cells into:

- **Benign**  
- **Malignant**  

The application aims to support cancer screening and early diagnosis.
---

## ➡️Introduction to SVM  

Support Vector Machine (SVM) is a supervised machine learning algorithm with strong classification capabilities. It works by optimizing the margin between data groups, which enhances accuracy and reduces errors.

In this notebook, you will use SVM (Support Vector Machines) to build and train a model using human cell records, and classify cells to whether the samples are benign or malignant.

SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not otherwise linearly separable. A separator between the categories is found, then the data is transformed in such a way that the separator could be drawn as a hyperplane. Following this, characteristics of new data can be used to predict the group to which a new record should belong.

---
## 📋 Table of contents

1. Load the Cancer data
2. Modeling
3. Evaluation

---
## 📊 Dataset Information  
The example is based on a dataset that is publicly available from the UCI Machine Learning Repository (Asuncion and Newman, 2007). The dataset consists of several hundred human cell sample records, each of which contains the values of a set of cell characteristics.The dataset contains 699 records, each sample includes features such as:
|Field name|Description|
|--- |--- |
|ID|Clump thickness|
|Clump|Clump thickness|
|UnifSize|Uniformity of cell size|
|UnifShape|Uniformity of cell shape|
|MargAdh|Marginal adhesion|
|SingEpiSize|Single epithelial cell size|
|BareNuc|Bare nuclei|
|BlandChrom|Bland chromatin|
|NormNucl|Normal nucleoli|
|Mit|Mitoses|
|Class|Benign or malignant|

---

## ⚙️ Tools & Technologies Used  

-  **Language**: Python 3.x  
-  **Libraries**:
  - scikit-learn – Machine Learning
  - pandas – Data Processing
  - numpy – Numerical Computation
  - matplotlib, seaborn – Data Visualization
-  **Jupyter Notebook** – Programming environment, visual, and presentation-friendly.

---



---

## 💡 Results & Practical Significance  
- **Accuracy** = 96%  
  → Correctly predicted 96% of all cases.

### Precision  
- **Benign**: 100%  
- **Malignant**: 90%

### Recall  
- **Benign**: 94%  
- **Malignant**: 100%

### F1-Score  
- **F1-Score** = 96%  
  → Balanced between accuracy and cancer detection.

### Actual Cancer Rate:  
- 47/137 test samples are cancerous (~34%).  
- 90/137 samples are benign (~66%).

### Confusion Matrix  
```python
[[85  5]  
 [ 0 47]]
