# Data_Science_and_ML

Project- Veronika.ipynb – the Jupyter notebook contains python code related to an assignment that requires data analysis and visualization of two datasets from the web with the broad topic of economic activity or measures for the region of Ann Arbor, Michigan, United States, or United States more broadly in order to answer a research question stated by me. Mainly pandas and matplotlib are used.

m_evaluation_VZ.ipynb – The notebook contains an assignment form coursera`s Applied Data Science with Python Specialization. The task was to train SVC (support vector classifier) and Logistic Regression classifier and to evaluate how effectively they predict instances of fraud using data based on this dataset from Kaggle, containing credit card transactions (features). 

Social_Network_FP_VZ.ipynb - This notebook I was working with a company's email network where each node corresponded to a person at the company, and each edge indicated that at least one email has been sent between two people. The network also contained the node attributes Department and ManagementSalary. Using NetworkX and the Graph (G), the code identifies the people in the network with missing values for the node attribute ManagementSalary and predicts whether or not these individuals are receiving a management position salary. The Gradient Boosting Classifier is used as model from sklearn library. The function salary_predictions() returns pandas data series containing the predicted probability that the corresponding employee is receiving a management position salary, and the index being the node id. The AUC of the model is 0.87.  
The other part of this assignment, was to predict future connections between employees of the network. The function new_connections_predictions() checks edges in graph G and predict whether or not these edges will have a future connection, using trained Gradient Boosting Classifier from sklearn. The function returns pandas data series containing the probability of the corresponding edge being a future connection. The evaluation metric for this assignment was the Area Under the ROC Curve (AUC). And the model`s AUC was 0.88.

Understanding_and_Predicting_Property_Maintenance_Fines_VZ.ipynb - This assignment is based on a data challenge from the Michigan Data Science Team (MDST). Given the data provided my task was to chose the proper features, to chose a model, to train it and evaluate it. After few checks, the Gradient Boosting Classifier was chosen and the function blight_model() returns pandas data series with the predictions as the probability that the corresponding blight ticket to be paid on time, and the ticket id as index. The evaluation metric when choosing the model for this assignment was the Area Under the ROC Curve (AUC) and the score received was around 0.76.
