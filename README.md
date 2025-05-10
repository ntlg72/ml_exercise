## Conclusions and Metrics

by Natalia López Gallego

### What Was Done?

A classification model was developed using multiple algorithms (Logistic Regression, Random Forest, SVM, and XGBoost) to predict a categorical target variable (`condition`) Based on product data. The process included:

* Cleaning and dropping irrelevant or redundant columns.
* Encoding categorical variables.
* Splitting the dataset into training and testing sets (80/20).
* Scaling features when necessary.

### Evaluation Metrics

Each model was evaluated using the following metrics:

* **Accuracy**: The proportion of correct predictions over the total.
* **F1-Score** (weighted): A balance between precision and recall, considering class imbalance.
* **ROC-AUC**: Area under the ROC curve (only for binary classification).

Results were compared to identify the model with the best overall performance.

### General Conclusions

* The best-performing model was \[**_**] based on the evaluated metrics.


NOTE: I experienced some technical problems with model training time, and it has not benn possible to obtain results fast.