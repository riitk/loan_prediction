# loan_prediction
Loan Prediction System using ML

# Loan Prediction using Machine Learning

This project aims to predict the approval status of loan applications using machine learning techniques. The dataset includes various attributes of applicants and the status of loan approval. We employ Logistic Regression and Support Vector Classifier (SVC) to build and compare models for prediction.

## Dataset

The dataset consists of the following columns:

- `Loan_ID`: Unique identifier for each loan application
- `Gender`: Gender of the applicant
- `Married`: Marital status of the applicant
- `Dependents`: Number of dependents
- `Education`: Education level of the applicant
- `Self_Employed`: Self-employment status of the applicant
- `ApplicantIncome`: Income of the applicant
- `CoapplicantIncome`: Income of the co-applicant
- `LoanAmount`: Loan amount requested
- `Loan_Amount_Term`: Term of the loan in months
- `Credit_History`: Credit history of the applicant (1: good, 0: bad)
- `Property_Area`: Area of the property (Urban, Semiurban, Rural)
- `Loan_Status`: Approval status of the loan (1: Approved, 0: Not Approved)

## Data Preprocessing

1. **Handling Missing Values**: 
   - Filled missing values with the mean of the respective columns.

2. **Dropping Useless Columns**: 
   - Dropped the `Loan_ID` column as it does not contribute to the prediction.

3. **Data Visualization**: 
   - Visualized data using various plots to understand the relationships between features and the target variable.

4. **Encoding Categorical Variables**: 
   - Converted categorical variables to numerical values using the `map` function.

5. **Splitting Data**: 
   - Performed train-test split to create training and testing datasets.

6. **Scaling Data**: 
   - Used `StandardScaler` to perform scaling on numerical features.

## Models Used

1. **Logistic Regression**: 
   - Trained the primary model using Logistic Regression.
   
2. **Support Vector Classifier (SVC)**: 
   - Used SVC for comparison with the Logistic Regression model.

## Evaluation

The models were evaluated using the following metrics:

- **Confusion Matrix**: To visualize the performance of the classification model.
- **Accuracy Score**: To measure the percentage of correctly predicted instances.
- **Classification Report**: To provide precision, recall, f1-score, and support for each class.

### Results

- **Logistic Regression**: Achieved an accuracy of 85.4%.
- **Support Vector Classifier**: Achieved an accuracy of 84.8%.


## How to Use

### Cloning the Repository

To clone the repository, use the following command:

```bash
git clone https://github.com/yourusername/loan-prediction.git
cd loan-prediction


