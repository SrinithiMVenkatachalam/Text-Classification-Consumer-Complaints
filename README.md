# Text Classification on Consumer Complaints

## Description
This project performs **text classification** on the Consumer Complaint dataset to categorize complaints into four categories:

1. Credit reporting, repair, or other  
2. Debt collection  
3. Consumer Loan  
4. Mortgage  

The workflow includes:  
- Exploratory Data Analysis (EDA)  
- Text preprocessing  
- Feature extraction using TF-IDF  
- Multi-class classification using Logistic Regression, Naive Bayes, and SVM  
- Model evaluation and predictions  

---

## Dataset
- **File:** `consumer_complaints_filtered.csv`  
- **Columns:** `Product`, `Consumer complaint narrative`, `label`  
- Filtered to include only the four product categories mentioned above.  

---

## How to Run
python text_classification.py

Model Evaluation

Accuracy and classification report are printed for each model.

Confusion matrix is displayed for the best-performing model.

The models included are:

Logistic Regression

Naive Bayes

SVM (LinearSVC)

