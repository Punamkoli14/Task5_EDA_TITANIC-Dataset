# Task5_EDA_TITANIC-Dataset
Project Title: Titanic Survival Analysis
📌 Objective:
To analyze the Titanic dataset and uncover insights about the survival patterns of passengers using data analysis and visualization techniques.

🗂️ Dataset Overview:
 working with the classic Titanic dataset, which includes features like:
 Passenger class (Pclass)
 Sex (Sex)
 Age (Age)
 Siblings/spouses aboard (SibSp)
 Parents/children aboard (Parch)
 Fare (Fare)
 Embarkation point (Embarked)
 Survival status (Survived)
 And some engineered features like family_size and family_type

🔧 Key Steps Performed:
✅ Data Cleaning:
Checked for null values

Handled missing data

✅ Feature Engineering:
Created a new column family_size using SibSp + Parch + 1

Derived family_type based on family_size:

Single, Small, Large

✅ Data Visualization:
Used Seaborn and Matplotlib for:

Countplots of survival rates by sex and Pclass

Heatmap showing correlation among numeric variables

Barplots and crosstabs to explore categorical relationships

✅ Encoding:
Applied One Hot Encoding to convert categorical columns:

Pclass, Sex, Embarked, and family_type

Used drop_first=True to avoid multicollinearity

📊 Key Insights:
Female passengers had a significantly higher survival rate than males.
Passengers from higher classes (Pclass=1) had better survival chances.
Embarked location and family size showed patterns in survival probability.
People in the age of 20 and 40 had a higher chance of not surviving.
People going to C survived more.
People travelling with samaller family had a higher chance of surviving the accidentin comparison to people with large family and travelling


📦 Tools & Libraries:
Python
Pandas
NumPy
Matplotlib
Seaborn
