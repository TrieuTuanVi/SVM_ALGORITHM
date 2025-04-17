# Project Pyhton - Machine Learning: 🧬SVM - based Cancer Cell Classification🧬

---

## 📌 Project Objective  
This project utilizes Support Vector Machines (SVM) to build a model that classifies human body cells into:

- **Benign**  
- **Malignant**  

The application aims to support cancer screening and early diagnosis.

---

## 💡 Introduction to SVM  
Support Vector Machine (SVM) is a supervised machine learning algorithm with strong classification capabilities. It works by optimizing the margin between data groups, which enhances accuracy and reduces errors.

---

## ⚙️ Tools & Technologies Used  
- 🐍 **Language**: Python 3.x  
- 📚 **Libraries**:
  - scikit-learn – Machine Learning
  - pandas – Data Processing
  - numpy – Numerical Computation
  - matplotlib, seaborn – Data Visualization
- 💻 **Jupyter Notebook** – Programming environment, visual, and presentation-friendly.

---

## 📊 Dataset Information  
The dataset contains 699 records, each sample includes features such as:
- Clump Thickness, Uniformity of Cell Size, Uniformity of Cell Shape, Bare Nuclei, Mitoses, etc.  
**Class**: 2 (Benign) or 4 (Malignant).

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
