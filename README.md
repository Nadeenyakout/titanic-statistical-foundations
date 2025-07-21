# titanic-statistical-foundations
# 📊 Titanic Data Preparation and Statistical Foundations for Machine Learning

 Objective
This project demonstrates essential data analysis and preparation techniques using the Titanic dataset from Kaggle. It focuses on applying key statistical concepts and practical preprocessing steps that are crucial before building any machine learning model.

---

 Dataset
- **Name:** Titanic – Machine Learning from Disaster  
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)  
- **File Used:** `train.csv`

---

 Tasks Covered

Part 1: Mathematical Foundations

#### 1. Central Tendency
- Calculated **Mean**, **Median**, and **Mode** for:
  - `Age`
  - `Fare`
  - `SibSp`
- Discussed what each measure indicates about the dataset.

2. Outlier Detection
- Detected outliers in the `Fare` column using **IQR method**.
- Visualized outliers with a **boxplot**.
- Commented on how outliers can affect model performance.

3. Normal Distribution Check
- Plotted histograms and KDE for `Age` and `Fare`.
- Analyzed if the distributions are normal and the implications for models like **Linear Regression** and **Naive Bayes**.

Part 2: Feature Engineering & Data Splitting

 1. Encoding and Transformation
- Applied **One-Hot Encoding** to `Sex` and `Embarked`.
- Used **StandardScaler** to normalize `Fare` and `Age`.

 2. Feature Creation
- Engineered two new features:
  - `FamilySize`: Sum of `SibSp`, `Parch`, and the passenger.
  - `Title`: Extracted from the `Name` field.
 3. Data Splitting
- Split the data into **Training (80%)** and **Testing (20%)** using `train_test_split` from Scikit-learn.
- Ensured **class balance** in the target variable `Survived`.

 🛠 Tools and Libraries Used
- Python
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn


Submission 
- ✅ A **ZIP file** containing the notebook/script and plots



---

## 🧾 Author
**Nadeen Ahmed**  
Healthcare Informatics Student – Alexandria University  
This project was completed as part of a university assignment on Data Preparation and Statistical Foundations for ML.
