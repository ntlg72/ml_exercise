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

* The best-performing model was \[**Model Name**] based on the evaluated metrics.
* Preprocessing steps such as encoding categorical variables and feature scaling were key, especially for models sensitive to feature scale like Logistic Regression.
* Model selection ultimately depends on the type of classification problem (binary vs. multiclass) and the intended use (e.g., precision vs. interpretability).

