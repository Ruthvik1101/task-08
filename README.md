Task-08 Report 

Decision Tree – Bank Marketing Subscription Prediction 


Objective: 

The objective of this task is to build a Decision Tree classification model to predict whether a customer will subscribe to a bank term deposit based on demographic and behavioral attributes. The task also focuses on making the model interpretable using decision rules and tree visualization. 

Tools Used

Python

Pandas

Scikit-learn

Matplotlib


Methodology: 

I have loaded the Bank Marketing dataset and explored its structure, feature types, and target variables. Relevant input features were separated from the target variable representing customer subscription behavior. Then I transformed the categorical variables into a numerical format using OneHotEncoder, while numerical features were retained without scaling. The ColumnTransformer and Pipeline are used to ensure consistent preprocessing and model training. The dataset was then split into training and testing sets using a fixed random state for reproducibility.  I have Trained the Decision Tree Classifier with limited depth to avoid overfitting. Finally, the model was evaluated using accuracy and classification metrics, and the decision tree was visualized for interpretability. 

Result and Analysis: 

The model achieved comparable training and testing accuracy, indicating controlled overfitting. 

The decision tree successfully captured important patterns related to customer subscription behavior. 

Visualization confirmed that the model is interpretable and suitable for explanation. 

Train-Test Split

The dataset was split into training and testing sets using:

80% training data

20% testing data

random_state=42 to ensure reproducibility

Conclusion: 

In this task, a Decision Tree model was successfully developed to predict bank term deposit subscriptions. Proper preprocessing, controlled tree depth, and evaluation ensured good performance and interpretability. The task enhanced understanding of decision trees, overfitting control, and rule-based model explanation, which are essential skills in interpretable machine learning. 
