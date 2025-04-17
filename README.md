# Project Pyhton - Machine Learning: 🧬SVM - based Cancer Cell Classification🧬

---
## 🔍 Casestudy

You are given a dataset consisting of records containing information about human body cells. You will use SVM (Support Vector Machines) to build and train a model to classify cells to determine whether samples are benign or malignant.

--- 

## 🎯 Project Objective  
This project utilizes Support Vector Machines (SVM) to build a model that classifies human body cells into:

- **Benign**  
- **Malignant**  

The application aims to support cancer screening and early diagnosis.

---

## 📃 Introduction to SVM  

Support Vector Machine (SVM) is a supervised machine learning algorithm with strong classification capabilities. It works by optimizing the margin between data groups, which enhances accuracy and reduces errors.

In this notebook, you will use SVM (Support Vector Machines) to build and train a model using human cell records, and classify cells to whether the samples are benign or malignant.

SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not otherwise linearly separable. A separator between the categories is found, then the data is transformed in such a way that the separator could be drawn as a hyperplane. Following this, characteristics of new data can be used to predict the group to which a new record should belong.

---
## 📋 Table of contents

1. Load the Cancer data
2. Modeling
3. Evaluation

---
## 📁 Dataset Information  

- <a href= "https://github.com/TrieuTuanVi/SVM_ALGORITHM/blob/main/knn_data.csv">Dataset</a>

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

## 🛠️ Tools & Technologies Used  

-  **Language**: Python 3.x  
-  **Libraries**:
    - scikit-learn – Machine Learning
    - pandas – Data Processing
    - numpy – Numerical Computation
    - matplotlib, seaborn – Data Visualization
-  **Jupyter Notebook** – Programming environment, visual, and presentation-friendly.

---
## ⚙️ Processing

**1. Data Preprocessing**
- Remove missing values, handle noise.
- Divide data into training and testing sets.

**2. Model Training**
- Apply SVM algorithm.
- Adjust kernel, C, gamma parameters to optimize performance.

**3. Model Evaluation** : Use Accuracy, Precision, Recall, F1-Score.

---
## ✅ Results 

    ![image](https://github.com/user-attachments/assets/99fc46ab-7566-4f14-afe9-58fd2574ecfd)

➡️ **Accuracy:** 96%
 
 --> The model predicted correctly 96% of the data, indicating a high overall accuracy.

➡️ **Precision:**
  - **Benign:** 100%
  - **Malignant:** 90%
    
-->  When the model predicts a sample as malignant (cancerous), the actual accuracy is 90%. When predicting benign (non-cancerous), the model's accuracy is nearly perfect (100%).

➡️ **Recall:**
  - **Benign:** 94%
  - **Malignant:** 100%
    
--> The model correctly identifies all malignant samples (recall of 100% for malignant). It detects 94% of benign samples correctly.

➡️ **F1-Score:** 96%

 
 --> The model maintains a good balance between precision and recall, making it suitable for medical applications where errors can have serious consequences.
 

    ![image](https://github.com/user-attachments/assets/63c822fc-2e3c-428f-9ba4-b0cff9e71cee)


➡️ **Cancer prevalence in the testing set:** ~34% (47 out of 137 samples)

 --> The dataset contains a relatively high proportion of cancer patients, and the model maintains strong performance despite this imbalance.

---
 
## 🌍 Impact & Application

- **Real-World Applications:**
  - Assists doctors in screening high-risk patients.
  - Increases accuracy in cancer diagnosis using cell data.
  - Reduces human error in sample evaluation during diagnosis.

- **Long-term Impact:**
  - Contributes to the integration of machine learning in healthcare.
  - Provides a foundation for automated diagnostic systems, reducing time and cost while enhancing early diagnosis and timely treatment.
 
    
---
## ✨ Conclusion

The SVM model delivers high accuracy, ensuring no cancer cases are missed. It is ideal for decision support systems in healthcare, contributing to early diagnosis and timely treatment.
