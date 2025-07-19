# 🎓 Predictive Analysis of Depression in Students using Feature Selection Techniques

## 📌 Aim
Mental health among students is an increasingly critical issue in today's high-pressure academic environments. This project explores a real-world dataset of over 27,000 students to uncover key predictors of depression and prepare the data for effective predictive modeling.

---

## 🎯 Objective
To uncover influential factors contributing to student depression using robust **feature selection techniques**, and provide insights that can support preventive strategies and mental health interventions.

---

## 🗂️ Dataset Overview
- **Name**: Student Depression Dataset  
- **Rows**: 27,901  
- **Features**: 18  
- **Target**: `Depression` (0 = No, 1 = Yes)  
- **Feature Types**: Categorical, Numerical, Ordinal  

Key features include:
- Gender, Age, City, Profession  
- Academic Pressure, Work Pressure, CGPA  
- Study & Job Satisfaction, Work/Study Hours  
- Sleep Duration, Dietary Habits, Financial Stress  
- Family History, Suicidal Thoughts  

---

## 🔧 Phase 1: Data Preprocessing
- Removed irrelevant columns (e.g., `id`)
- Converted Yes/No responses to binary
- Mapped ordinal values for sleep and dietary habits
- Handled missing values using median/mode
- Applied label encoding and one-hot encoding
- Standardized numeric features for modeling

---

## 📊 Phase 2: Visualization
- Histograms for numerical distribution
- Box plots for outlier detection
- Bar charts for categorical feature frequency
- Correlation heatmap to analyze inter-feature relationships

---

## 🔍 Phase 3: Feature Selection Techniques
### Filter Method
- ✅ **Chi-Square Test**
- ✅ **Mutual Information**

### Wrapper Method
- ✅ **Recursive Feature Elimination (RFE)** with Logistic Regression

### Embedded Method
- ✅ **Decision Tree Feature Importance**

---

## 🔁 Phase 4: Comparing Selected Features
Top repeatedly selected features across methods:
- `Academic Pressure`
- `Financial Stress`
- `Suicidal Thoughts`
- `Age`
- `Work/Study Hours`
- `Sleep Duration`

---

## 📈 Phase 5: Final Visualizations & Insights
- Bar plots of top features (MI and Tree importance)
- Correlation heatmaps of final selected features
- Frequency bar chart of overlapping selected features

---

## 💡 Key Insights
- **Academic Pressure**, **Financial Stress**, and **Suicidal Thoughts** were the top predictors of depression.
- **Sleep Duration** and **Work/Study Hours** were also significantly correlated.
- Environmental, emotional, and lifestyle factors all contribute meaningfully to student depression.

---

## 📁 Files Included
- `student_depression_dataset.csv`: Raw dataset
- `cleaned_student_depression_dataset.csv`: Preprocessed dataset
- `student_depression_scaled.csv`: Final encoded and scaled dataset
- `notebook.ipynb`: Full analysis notebook (Colab compatible)

---

## 🚀 Future Work
- Apply machine learning models for depression prediction  
- Implement SHAP/LIME for model explainability  
- Build a lightweight dashboard for mental health insights

---

## 🤝 Acknowledgements
Thanks to all contributors and data providers enabling mental health research in the student community.

---

## ✍️ Author
**By Siddarth Valasubramanian**

---

## 📌 License
This project is for educational and research purposes only.
