# Telco_Customer_Churn_Prediction
![Churn1-1024x724](https://user-images.githubusercontent.com/79527973/212547141-d40899d5-1bf3-4557-9ffb-2856338d7db0.jpg)

### Customer Churn Prediction
Customer churn prediction is to measure why customers are leaving a business. We will build a deep learning model to predict the churn and use precision,recall,f1-score to measure performance of our model

We use Python and the Pandas library to load a customer information dataset from a CSV file and then perform some data cleaning and manipulation tasks on the dataset. The dataset contains information about a telecommunications company’s customers, including their demographics, service usage, and whether they are lost (i.e., whether they have ceased to be customers).

After that, the next step in this process would typically be to perform some exploratory data analysis (EDA) on the dataset to gain insights into the data and identify patterns or relationships that could be useful for building a predictive model. This might involve creating visualizations, such as histograms or scatter plots, to explore the distribution of different features or the relationship between different features and the target variable (churn).

          Churn precision    recall  f1-score   support

           0       0.82      0.86      0.84       999
           1       0.62      0.54      0.57       408

    accuracy                           0.77      1407
   macro avg       0.72      0.70      0.71      1407
weighted avg       0.76      0.77      0.76      1407

The classification report gives us a summary of the model’s performance on the test set. It includes the following metrics:

* Precision: Precision is the proportion of true positive predictions to all positive predictions. It is a measure of how many of the positive predictions are actually correct. A high precision means that the model is not returning many false positives.

* Recall: Recall is the proportion of true positive predictions to all actual positive observations. It is a measure of how many of the actual positives the model is able to identify. A high recall means that the model is not missing many actual positives.

* F1-Score: The F1-score is a harmonic mean of precision and recall. It ranges from 0 to 1, with 1 being the best score. The F1-score is a good measure of a model’s overall performance, as it balances precision and recall.

* Support: Support is the number of observations for each class.

* Accuracy: Accuracy is the proportion of correct predictions to all predictions. It is a measure of how well the model is able to predict the class labels.

* Macro avg: Macro avg is the unweighted mean of precision, recall and f1-score across all classes.

* Weighted avg: Weighted avg is the weighted mean of precision, recall and f1-score across all classes.

For More: Visit my [Medium account](https://medium.com/@ahmettsdmr1312)
