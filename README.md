# Titanic-Dataset---Exploratory-Data-Analysis-EDA
# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract insights, identify trends, and highlight factors influencing passenger survival.

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Steps Performed
1. **Data Cleaning**
   - Handled missing values (`Age` → median, `Embarked` → mode, `Cabin` dropped).
   - Removed duplicates.
   - Checked data types and structure.

2. **Exploratory Analysis**
   - Univariate: Histograms, boxplots for Age, Fare.
   - Bivariate: Survival vs Sex, Class, Embarked.
   - Multivariate: Pairplots, correlation heatmap.

3. **Key KPIs**
   - Overall survival rate.
   - Survival by gender, class, and family size.
   - Age and fare distributions.
   - Embarked port distribution.

---

## 📈 Key Findings
- Overall survival rate ≈ 38%.
- Female passengers had much higher survival chances (~74%) compared to males (~19%).
- First-class passengers had the highest survival (~63%), third-class the lowest (~24%).
- Families had better chances of survival compared to solo travelers.
- Younger passengers had higher survival rates.
