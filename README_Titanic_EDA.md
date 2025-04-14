
# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis (EDA) on the Titanic dataset using Python libraries like Pandas, Seaborn, and Matplotlib.

---

## 📂 Files Used

- `train.csv` — Main dataset for EDA (from Titanic competition on Kaggle)

---

## 🔧 Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📋 Steps Performed

1. **Data Loading and Overview**
   - Used `.info()`, `.describe()`, and `.value_counts()` to understand data structure and distributions.

2. **Univariate Analysis**
   - Plotted histograms of features like `Age`, `Fare`, `SibSp`, `Parch`.

3. **Bivariate Analysis**
   - Bar plots for `Sex` vs `Survived` and `Pclass` vs `Survived`.
   - Boxplot and scatterplot for `Fare` vs `Survived`, `Age` vs `Fare`.

4. **Multivariate Analysis**
   - Pairplot for relationships between `Age`, `Fare`, `Pclass`, `Sex`, and `Survived`.

5. **Correlation Analysis**
   - Heatmap showing correlation among numerical variables.

---

## 🔍 Key Relationships & Trends

### 🧑‍🤝‍🧑 Gender vs Survival
- **Females had a significantly higher survival rate** than males.
- One of the **strongest predictors** of survival.

### 🎟️ Passenger Class (Pclass) vs Survival
- **1st class passengers** had the highest survival rate.
- Clear **correlation between wealth and survival**.

### 📈 Fare vs Survival
- Higher-paying passengers were more likely to survive.
- Positive correlation with survival.

### 🧒 Age vs Survival
- **Children under 10** had a relatively **higher chance of survival**.
- Elderly had lower survival chances.

### 👨‍👩‍👧‍👦 Family Size vs Survival
- Passengers traveling **alone** were less likely to survive.
- Small families had better outcomes.

### 📊 Correlation Heatmap
- `Fare` is **positively correlated** with survival.
- `Pclass` and `Sex` (encoded) also show strong correlation with outcome.

---

## ✅ Summary Table

| Feature         | Trend with Survival             |
|---------------- |---------------------------------|
| Sex             | Females > Males                 |
| Pclass          | 1st class > 2nd > 3rd           |
| Fare            | Higher fare = more survival     |
| Age             | Children more likely to survive |
| Family Size     | Alone = lower survival          |

---

## 📁 Output

All analysis is done in a Jupyter Notebook and visualized using Seaborn and Matplotlib.

## Files Attached
-Titanic.ipynb -- Jupyter Notebook
-Survival Analysis of the Titanic Dataset.pptx -- PDF report of findings
---

This project is licensed under the MIT License.
