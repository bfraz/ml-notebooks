# ml-notebooks

## Setup

#### 1. Install Visual Studio Code:
   - https://code.visualstudio.com/download
#### 2. Install VS Code Extensions:
   - Jupyter<img width="1246" alt="Screenshot 2024-10-16 at 6 40 36 PM" src="https://github.com/user-attachments/assets/9b682429-ab25-4741-ac15-9b1b817f8ff4">
   - Python<img width="1246" alt="Screenshot 2024-10-16 at 6 43 51 PM" src="https://github.com/user-attachments/assets/38c33670-e0a1-4a90-8e12-cd5157436488">
#### 3. Install Notebook-Specific Dependencies (may not be necessary)
   - Uncomment first line of "Importing Libraries" cell and run<img width="882" alt="Screenshot 2024-10-16 at 6 50 58 PM" src="https://github.com/user-attachments/assets/d0f8b4c6-41c6-4d52-8cf3-6bbf3176510a">

### Logistic Regression Notebooks

1. Customer Churn
   - Dataset: https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset
       1. Importing Libraries
          - pandas numpy matplotlib seaborn scikit-learn
       2. Read in Dataset
          - csv -> pandas dataframe
       3. Data Inspecting and Cleaning
          - resolve missing values, null values, np.nan and duplicated rows
          - categorical features replaced with numerical values
          - customer_id column is removed
          - check for removable outliers
       4. Exploratory Data Analysis
          - statistical metrics (mean, standard deviation etc)
       6. Feature Splitting and Scaling
          - divide the dataset into training and testing sub-datasets
       7. Predictive Modeling
          - train model on training dataset
          - test model on testing dataset
          - model performance
            - confusion matrix, accuracy, precision, recall, f1-score 
   
2. Diabetes
   - Dataset: https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
       1. Importing Libraries
          - pandas numpy matplotlib seaborn scikit-learn
       2. Read in Dataset
          - csv -> pandas dataframe
       3. Data Inspecting and Cleaning
          - resolve missing values, null values, np.nan and duplicated rows
          - categorical features replaced with numerical values
          - check for removable outliers
       4. Exploratory Data Analysis
          - statistical metrics (mean, standard deviation etc)
       6. Feature Splitting and Scaling
          - divide the dataset into training and testing sub-datasets
       7. Predictive Modeling
          - train model on training dataset
          - test model on testing dataset
          - model performance
            - confusion matrix, accuracy, precision, recall, f1-score 
 
