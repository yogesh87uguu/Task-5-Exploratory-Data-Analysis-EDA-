# Task-5-Exploratory-Data-Analysis-EDA-
 Extract insights using visual and statistical exploration.

---

## 🎯 Objective

- Understand the structure and content of the Titanic dataset.
- Explore relationships between variables and the target (`Survived`).
- Visualize the data for better interpretation.
- Summarize key findings with appropriate plots and statistics.

---

## 🛠 Tools & Libraries Used

- **Python 3**
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **Matplotlib & Seaborn** – for data visualization
- **Jupyter Notebook** – for interactive data analysis

---

## 📊 Key Insights from EDA

### 🔍 Missing Values:
- `Age`: 177 missing entries
- `Cabin`: 687 missing entries
- `Embarked`: 2 missing entries

### 👥 Survival Trends:
- **Sex**: Females had a much higher survival rate than males.
- **Pclass**: Passengers in 1st class were more likely to survive.
- **Age**: Younger passengers (especially children) had better chances.
- **Fare**: Passengers who paid higher fares tended to survive more.

### 📈 Correlations:
- `Pclass` is negatively correlated with `Fare`.
- `Parch` and `SibSp` are moderately positively correlated.
- `Fare` and `Survived` have a weak positive correlation.

---

## 📸 Visualizations Included

- Heatmap of missing values
- Histograms for numerical columns
- Boxplots: `Age` & `Fare` vs `Survived`
- Countplots: `Sex` vs `Survived`, `Pclass` vs `Survived`
- Correlation heatmap

All plots are saved in the `eda_images/` folder and embedded in the Jupyter Notebook.

---

## 🧾 How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   cd titanic-eda
