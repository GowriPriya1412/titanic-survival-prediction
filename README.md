# titanic-survival-prediction
This project uses Python and machine learning to predict passenger survival on the Titanic using the famous Kaggle dataset. It demonstrates data cleaning, feature engineering, exploratory analysis, and predictive modeling.

Project Overview
The objective is to build a classification model to predict whether a passenger survived the Titanic disaster based on features like age, sex, class, etc.

The workflow includes:
1. Data preprocessing
2. Exploratory data analysis (EDA)
3. Feature engineering
4.  Model training & evaluation

Dataset
Source: Kaggle Titanic Dataset
Files Used:
train.csv — training data with features + labels
test.csv — testing data without labels (for prediction)

Tools & Libraries
1. Python
2. Pandas
3. NumPy
4. Matplotlib / Seaborn
5. Scikit-learn (Logistic Regression, Random Forest, etc.)
6. Jupyter Notebook

Key Steps
1. Data Preprocessing
Handling missing values (e.g., Age, Cabin)
Encoding categorical variables (e.g., Sex, Embarked)
Feature selection and creation (e.g., FamilySize)

2. Exploratory Analysis
Visualizing survival distribution by gender, class, etc.
Correlation heatmaps and bar plots

3. Modeling
Logistic Regression
Decision Tree / Random Forest
Evaluation using accuracy score, confusion matrix

Results
Best model: Random Forest Classifier (or whichever model performed best)
Accuracy: XX% (mention your actual result)
Key predictors: Sex, Pclass, Age, etc.

How to Run
1. Clone the repository:
   git clone https://github.com/GowriPriya1412/titanic-survival-prediction.git
2. Navigate to the folder:
   cd titanic-survival-prediction
3. Run the notebook: Open Titanic solution-checkpoint.ipynb in Jupyter or VS Code.

Key Insights from Titanic Survival Prediction
Survival Distribution:
1. About 38% of passengers survived, while 62% did not survive, as shown by the class distribution in the pie chart.
2. This highlights the harsh survival conditions during the disaster.

Gender Matters:
1. A higher proportion of female passengers survived compared to males.
2. This aligns with the “women and children first” evacuation policy followed on the Titanic.

Passenger Class Influence:
1. Among female passengers, most were traveling in 3rd class, followed by 1st and 2nd class.
2. Despite the large number in 3rd class, survival rates were higher for 1st class passengers, likely due to quicker access to lifeboats.

Young Females Had Better Chances:
1. Females under 30 had a higher survival rate than other age groups.
2. This could be attributed to prioritization during evacuation.

Data Preprocessing Included:
1. Handled missing values (like Age)
2. Explored distributions using value_counts(), describe(), and pie charts
3. Visualized survival rates by gender and class using Matplotlib

Author:
1. Gowri Priya
2. www.linkedin.com/in/gowripriya1412
