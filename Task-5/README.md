# 🧠 Task 5: Decision Trees and Random Forests - AI & ML Internship

## 📌 Objective
To understand and implement tree-based models (Decision Trees and Random Forests) for classification tasks. The goal is to visualize decision trees, evaluate model performance, and interpret feature importance.

---

## 📁 Dataset
**Heart Disease Dataset**

- **Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) or [Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Target Column**: `target` (1 = heart disease, 0 = no heart disease)

---

## ⚙️ Tools & Libraries
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Graphviz (optional for tree visualization)

---

## 📊 Steps Performed

1. **Data Loading & Preprocessing**  
   Loaded the Heart Disease dataset, checked for missing values, and split it into features (`X`) and target (`y`).

2. **Train-Test Split**  
   Divided data into training and testing sets (80% train, 20% test).

3. **Decision Tree Classifier**
   - Trained a Decision Tree with limited depth to prevent overfitting.
   - Visualized the decision tree using `plot_tree`.
   - Evaluated performance using accuracy and classification report.

4. **Random Forest Classifier**
   - Trained a Random Forest with 100 estimators.
   - Compared its accuracy with Decision Tree.
   - Performed cross-validation to assess model stability.
   - Extracted and plotted feature importance scores.

5. **Visualization**
   - Displayed tree structure using `matplotlib`.
   - Plotted bar graph of feature importances.

---

## ✅ Results

| Model             | Accuracy |
|------------------|----------|
| Decision Tree     | ~XX%     |
| Random Forest     | ~YY%     |
| Cross-Validation (RF) | ~ZZ% |

*(Replace XX, YY, ZZ with your actual results)*

---

## 📌 Key Learnings

- Decision Trees are interpretable but prone to overfitting.
- Random Forests provide better generalization by averaging multiple trees.
- Feature importance helps in identifying key drivers of prediction.
- Overfitting can be controlled using `max_depth`, `min_samples_split`, etc.
- Cross-validation provides a more reliable estimate of model performance.

---

## 📁 Repository Structure

📦 Task5_DecisionTrees
├── heart.csv # Dataset
├── Task5_DecisionTree_RF.ipynb # Notebook file with all steps
├── tree_visualization.png # (Optional) Tree plot
├── README.md # This file

## Screenshots

![image](https://github.com/user-attachments/assets/76e70cdf-c224-4b7a-8503-312fa6a52d0c)
![image](https://github.com/user-attachments/assets/ec952e32-ac75-47a2-a18d-9de8ca6e1ba0)

