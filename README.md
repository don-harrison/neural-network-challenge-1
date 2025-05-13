# Student Loan Repayment Prediction

## Overview
You work at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate. Your team has asked you to build a model to predict student loan repayment.

The business team has provided a CSV file containing information about previous student loan recipients, including their credit rankings and other attributes. You will use this dataset to train a neural network that predicts the likelihood an applicant will repay their loan.

## Dataset
- **Source:**  
  https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv  
- **Target column:** `credit_ranking`  
- **Features:** All other columns in the CSV

## Project Tasks
1. **Data Preparation**  
   - Read the CSV into a Pandas DataFrame  
   - Inspect columns to identify potential features and the target variable  
2. **Feature & Target Creation**  
   - Define **X** (features) as all columns except `credit_ranking`  
   - Define **y** (target) as `credit_ranking`  
3. **Train/Test Split**  
   - Split **X** and **y** into training and testing sets  
4. **Feature Scaling**  
   - Apply `StandardScaler` from scikit‑learn to scale the feature data  
5. **Model Design**  
   - Use TensorFlow’s Keras API to create a deep neural network  
   - Determine the number of input neurons based on feature count  
   - Choose an appropriate number of hidden layers and neurons per layer  
6. **Compile & Train**  
   - Compile the model with a suitable loss function and optimizer  
   - Fit the model on the training data  
7. **Evaluation**  
   - Evaluate model performance on the test set (loss and accuracy)  
8. **Prediction**  
   - Use the trained model to predict loan repayment success  
9. **Recommendation System Discussion**  
   - Outline how you would extend or adapt this work into a recommendation system for student loans

## Usage
1. Clone this repository  
2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn tensorflow
