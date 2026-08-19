# 🩺 Diabetes Analysis — EDA
<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![EDA](https://img.shields.io/badge/EDA-Exploratory_Data_Analysis-purple)

</p>
An Exploratory Data Analysis project focused on understanding the factors associated with diabetes outcomes and identifying important patterns among clinical and demographic features.

## 🎯 Objective
Analyze the distribution of diabetes outcomes.
Understand relationships between clinical features and diabetes.
Identify the strongest factors associated with diabetes.
Explore interactions between multiple risk factors.
Validate initial hypotheses through visual and statistical analysis.

---

## 🛠️ Tools Used
🐍 Python
🐼 Pandas
🔢 NumPy
📊 Matplotlib
🎨 Seaborn

---

## 🧹 Data Cleaning
🔍 Checked feature distributions and data quality.
⚠️ Identified unrealistic 0 values in features such as BMI, Insulin, and SkinThickness.
🧹 Treated these values as missing data where appropriate.
📈 Applied a log transformation to Insulin to reduce extreme right-skewness.
📊 Used descriptive and correlation analysis to understand the dataset.

---

## 📈 EDA & Key Insights
🍬 Glucose showed the strongest relationship with diabetes outcome.
⚖️ BMI was generally higher among diabetic individuals.
💉 Insulin showed a positive relationship with diabetes but contained strong skewness and outliers.
🎂 Age showed a clear positive relationship with diabetes.
🧬 Higher Diabetes Pedigree Function values were generally associated with diabetic individuals.
🤰 Higher numbers of pregnancies showed an increasing proportion of diabetes in several groups.
🩸 Blood Pressure showed only a weak relationship with diabetes.
📊 Multivariate analysis showed that combining Glucose, BMI, Insulin, and Age provides a clearer picture than analyzing individual features alone.

---

## 🔗 Multivariate Analysis

The analysis explored relationships between:

🍬 Glucose & Age
⚖️ BMI & SkinThickness
💉 Glucose, BMI & Insulin
🎂 Age, Glucose & BMI
🔥 Multiple clinical features using correlation and pairwise analysis

These visualizations revealed noticeable high-risk clusters where multiple risk factors occur together.

---

## 💡 Conclusion

The analysis shows that diabetes is influenced by multiple interacting factors rather than a single variable. Glucose emerged as the strongest indicator, while BMI, Insulin, Age, and Diabetes Pedigree Function provided additional information. Overall, the multivariate analysis demonstrated that combining several clinical features gives a much clearer understanding of diabetes risk than relying on any single feature.
