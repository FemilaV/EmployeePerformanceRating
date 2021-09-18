# EmployeePerformanceRating
              The dataset  was clean and well structured with 28 features and 1200 rows.Identified variable- PerformanceRating as the Target(Independent Variable).As mentioned the data was clean so there were no null values.There were 9 categorical variables and 19 numerical variables.Used Label Encoding technique to convert categorical variables to Numerical.
The box plots were showing that there were outliers in the dataset so removed the outliers z-score greater than 3 standard deviation.Removed 66 outliers.
The dataset was imbalanced.There were 831 rows with Performance rating '3',177 rows with a roting of '2' and 126 rows with a rating of '4'.So applied SMOTE Oversampling to balance the dataset.
Used Matplotlib ,Seaborn and Plotly for Graphs. Barplots,Histograms,Scatterplots,Violin plots were used for analysing the factors affecting the Performance of the employees in each department.
WorkLifeBalance,BusinessTravelFrequency,EmpEnvironmentSatisfaction are the 3 important Factors effecting employee performance.
Higher the worklife balance and higher theEmpEnvironmentSatisfaction higher the performance.In HumanResource,Research and development Finance departments non travellers are showing higher performance.
Applied SelectKBest,ExtraTreeClassifier and Pearson Correlation for Feature Selection,removed Age and EmpHourlyRate as both have the weakest relationship with the target(performanceRating).
Applied DecisionTree, Random Forest, XGBoost,K Means and SupporVectorMachine Classifier model alorithms.Random Forest gave an accuracy of 97 and XGBoost gave an accuracy of 96.
Printed the classification report and Confusion Matrix
