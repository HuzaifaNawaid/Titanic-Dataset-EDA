# 🚢 Titanic Survival Analysis – EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the famous **Titanic: Machine Learning from Disaster** dataset.  
We explore passenger data to understand survival patterns using **Python, Pandas, Seaborn, and Matplotlib**.

---

## 📂 Dataset
We use the `train.csv` file from [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic).  
It contains information like:
- Passenger class
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Fare price
- Embarkation port
- Survival status (0 = No, 1 = Yes)

---

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas – data handling
- Seaborn – data visualization
- Matplotlib – plotting
- Jupyter Notebook – interactive coding

---

## 🔍 Steps Performed
1. **Load Dataset** – Read `train.csv` into a Pandas DataFrame.
2. **Data Overview** – Check columns, types, and missing values.
3. **Data Cleaning**  
   - Fill missing `Embarked`, `Age`, and `Fare`.
   - Create new features: `HasCabin`, `Sex_code`, `FamilySize`, `IsAlone`, and `Title`.
4. **Basic Insights** – Calculate survival rates by gender, class, and other features.
5. **Visualizations**  
   - Survival rate by gender
   - Survival rate by class
   - Correlation heatmap
   - Survival by gender & class heatmap
6. **Save Cleaned Data** – Export processed data to `titanic_cleaned.csv`.

---

## 📊 Example Insights
- **Females** had a much higher survival rate than males.
- **First-class passengers** survived more often than third-class.
- Passengers **with cabins** had higher survival chances.
- Being **alone** lowered survival chances.

## 📜 License
This project is distributed under the **MIT License**. See `LICENSE` for more information.

## 📞 Contact
**Huzaifa Nawaid**  
Email: huzaifanawaid.developer@gmail.com 
