Projects: Iris Flower Prediction and Salary Prediction
1. Iris Flower Prediction
In this project, I used the Iris Dataset to predict the species of an iris flower based on its sepal length, sepal width, petal length, and petal width.

Data Preprocessing:
I imported the dataset from Scikit-learn and used Matplotlib for data visualization. To visualize relationships between features, I used Seaborn's heatmap to identify feature correlations. The heatmap showed that petal length and petal width were more strongly correlated than sepal length and sepal width.

Model Training and Evaluation:
For classification, I used Logistic Regression, a commonly used model when the features have a linear relationship with the target. I performed a train-test split to evaluate the model's performance. The model achieved a perfect accuracy score of 1, indicating that Logistic Regression was a suitable choice for this dataset.

2. Salary Prediction Based on Degree and Job
In this project, I predicted the salary of employees based on their degree and job.

Data Preprocessing:
I used Label Encoding from Scikit-learn to convert categorical data (job titles and degree types) into numerical values for the model.

Model Training and Evaluation:
For prediction, I applied the Decision Tree Classifier to model the relationship between the features and the target variable (salary). The decision tree worked well to predict the salary based on the input features.

The model predicted the salary effectively, demonstrating the power of decision trees in handling both categorical and continuous data.

Key Takeaways:
1. Used Label Encoding to convert categorical data (job titles, degree types) into numerical values.
2. Employed Logistic Regression to predict Iris flower species based on its features, achieving perfect accuracy.
3. Utilized Decision Tree Classifier for salary prediction and explored the model's performance through feature importance and train-test split.
4. Visualized data with Matplotlib and Seaborn, using heatmaps to identify important feature correlations.









