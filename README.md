Customer Purchase Prediction using Logistic Regression:-

This project demonstrates how to apply Logistic Regression to predict customer purchase decisions based on their age. The model leverages the popular machine learning library scikit-learn and includes steps for data preprocessing, model training, evaluation, and visualization. It is designed to help understand customer behavior through age-based prediction of whether a customer makes a purchase.

Table of Contents
1.Overview
2.Dataset
3.Requirements
4.Model Workflow
5.Results and Evaluation
6.Usage
7.License

1)Overview:-
The objective of this project is to create a machine learning model that predicts whether a customer will make a purchase based on their age. The dataset used for this project contains two columns: customer age and purchase decision (binary: 1 for a purchase, 0 for no purchase).

A Logistic Regression model is trained on this data, and the performance is evaluated using various metrics like accuracy, confusion matrix, and classification report. Data visualization is used to better understand the relationship between customer age and purchase decisions.

2)Dataset:-
The dataset used in this model is stored in the file business_logistic_regression_dataset.csv. It consists of the following columns:

Customer_Age: The age of the customer.
Purchase_Decision: A binary variable indicating whether the customer made a purchase (1 for purchase, 0 for no purchase).
Ensure that the dataset is placed in the same directory as the script when running the model.

3)Requirements:-
To run this model, you need to install the following Python libraries:

numpy: For numerical computations.
pandas: For data manipulation and analysis.
matplotlib: For creating static, animated, and interactive visualizations.
seaborn: For statistical data visualization.
scikit-learn: For machine learning algorithms and tools.
You can install these dependencies using pip.

4)Model Workflow:-
Data Preprocessing:
The dataset is first loaded and checked for missing values. The feature (customer age) is extracted and scaled using StandardScaler to standardize the data, ensuring that the model is not biased by features with larger scales.

Model Training:-
The data is split into training and testing sets. A logistic regression model is then trained using the training data. This model predicts whether a customer will make a purchase based on their age.

Model Evaluation:
After training, the model is evaluated on the test set. The evaluation includes accuracy, a confusion matrix, and a classification report that shows precision, recall, and F1-score for both classes (purchase or no purchase).

Visualization:
Two visualizations are produced:

A scatter plot showing the relationship between customer age and purchase decision.
A heatmap of the confusion matrix, providing a clearer view of the true vs. predicted values.

5)Results and Evaluation:-
Accuracy: The model's accuracy score indicates how well it performs on unseen test data.

Classification Report: The classification report provides the precision, recall, and F1-score for both the purchase and no purchase classes, helping to assess the model’s performance in detail.

Confusion Matrix: The confusion matrix is used to visualize how many predictions were correct and how many were incorrect, providing a direct view of model performance.

Visualization: The scatter plot visually depicts how customer age correlates with their purchase decision, while the confusion matrix heatmap further aids in evaluating the model's performance.

6)Usage:-
Clone the repository to your local machine.
Place the business_logistic_regression_dataset.csv file in the same directory.
Run the Python script to train the model, make predictions, and view the results.

7)License:-
This project is licensed under the MIT License - see the LICENSE file for details.
