# Breast Cancer
The objective of this project is to determine based on the data of the tumor whether the person gets malignant or benign cancerous tumor. 
Using SVM or support-vector machines algorithm/model, I was able to predict correctly up to 98% of the testing data. In addition, I compared the effiency and accuracy of KNN and SVM algorithm and draw a conclusive finding: SVM is more often better than KNN in classification problems.
# Install and Run the Project
This project requires installed Python library: scikit-learn

Note: the breast cancer data is included when we download scikit-learn. You can access it by including this import and function below:
```
from sklearn import datasets
cancer = datasets.load_breast_cancer()
```
