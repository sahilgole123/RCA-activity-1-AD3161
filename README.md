CIE 2 – Activity 1: Simple Linear Regression
Student Details
- Name: Sahil Gole
- Roll Number: AD3161
- Course: Regression and Classification Algorithms (RCA)
- Department: Artificial Intelligence and Data Science
- College: Zeal College of Engineering and Research
1. Objective
To implement a Simple Linear Regression model using Python to study the relationship between years of work experience and salary, and to predict salary based on years of experience.
2. Dataset Details
- Dataset file: Salary_dataset.csv
- Number of records: 30
- Columns in the dataset: Unnamed: 0, YearsExperience, Salary
- Input feature (X): YearsExperience
- Target variable (y): Salary
- Dataset source: Kaggle (add the exact Kaggle dataset URL here before submitting).
The Unnamed: 0 column is an index-like column and is not used as a model input.
3. Tools and Libraries
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
4. Work Completed
1. Imported the required Python libraries.
2. Loaded the salary dataset.
3. Inspected the dataset information and descriptive statistics.
4. Checked for missing values.
5. Created a scatter plot to study the relationship between experience and salary.
6. Selected YearsExperience as the input feature and Salary as the target.
7. Split the data into training and testing sets using an 80:20 split.
8. Trained a Simple Linear Regression model.
9. Predicted salary values for the test data.
10. Plotted the regression line.
11. Evaluated the model using MAE, MSE, RMSE and R-squared.
12. Used the trained model to predict salary for a new experience value.
5. Model Equation
The fitted regression equation from the notebook is:

Salary = 24380.2015 + (9423.8153 × YearsExperience)
- Intercept: 24380.2015
- Slope: 9423.8153
The slope indicates that the model estimates an increase of approximately 9,423.82 salary units for each additional year of experience.
6. Model Evaluation Results
The notebook reports the following test-set results:
Metric	Result
Mean Absolute Error (MAE)	6286.45
Mean Squared Error (MSE)	49830096.86
Root Mean Squared Error (RMSE)	7059.04
R-squared (R²)	0.9024


The test R² value of approximately 0.9024 indicates that the model explains about 90.24% of the variation in salary in this test set. MAE and RMSE describe the prediction error in salary units.
7. Example Prediction
For 5 years of experience, the notebook predicts a salary of approximately 71,499.28.
8. Conclusion
A Simple Linear Regression model was trained to estimate salary using years of experience. The model produced an R² score of approximately 0.9024 on the test data. The result shows a strong relationship in this dataset, but predictions are estimates and may be affected by other factors not included in the model.
9. Project Files
- Simple_Linear_Regression.ipynb – Python notebook containing the code, outputs and plots.
- Salary_dataset.csv – Dataset used for the activity.
- README.md – Project description and summary.
- https://github.com/complexiota
