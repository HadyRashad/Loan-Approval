
<br/>
<div align="center">

<h3 align="center">Loan Approval Prediction using Machine Learning</h3>
<p align="center">
Loan prediction is a common problem faced by financial institutions. This project provides an AI-driven solution for predicting the approval of loan applications. The dataset used in this project includes factors like applicant details, loan size, and more. The model can help streamline loan approval processes by predicting approvals based on provided data.


  


</p>
</div>

## About The Project

This project is designed to predict loan approval decisions using machine learning algorithms. The goal is to automate the process of determining whether a loan should be approved based on several factors, such as an applicant's credit history, income, loan amount, and employment details. By leveraging machine learning models, we aim to provide more accurate and faster predictions, enhancing the efficiency of financial institutions.

<b>Project Workflow</b> <br>
<ol>
<li>Data Preprocessing:</li>
<ol>
<li>Handle missing values.</li>
<li>Convert categorical variables to numeric format.</li>
<li>Scale numeric features.</li>
</ol>
<li>Model Building:</li>

Several machine learning models are implemented, including:
<ol>
<li>Logistic Regression</li>
<li>Decision Trees</li>
<li>Random Forest</li>
<li>Support Vector Machine (SVM)</li>
<li>XGBoost</li>
</ol> <br>
<li>Model Evaluation:</li>
Models are evaluated using accuracy, precision, recall, and F1-score. Cross-validation techniques are also applied to ensure the model's generalization to unseen data.
The best-performing model in this project was the Random Forest, with an accuracy of 84%.
Key Features of the Project
Data Handling: Preprocessing steps such as imputing missing values, scaling, and encoding categorical features are automated for cleaner input data.
Multiple ML Algorithms: Different algorithms are tested to compare their performances, allowing for a better understanding of which model fits the data best.
Evaluation Metrics: In addition to accuracy, metrics such as precision and recall ensure that the model is reliable in identifying both approvals and denials.
User-Friendly Predictions: The final model can be used to make predictions for new applicants based on their input data.
</ol>

### Built With

The dataset used for this project contains various details about loan applicants, including demographic information, credit history, and loan amount requested. It consists of 13 features such as Gender, Married, Education, ApplicantIncome, and Credit_History, with the target variable being Loan_Status (approved or not approved). The dataset is split into training and testing sets to evaluate the model's performance.

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.
### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm install pandas scikit-learn xgboost
  ```
### Installation

<ol>
<li>Clone the repository to your local machine.
<li>Install the necessary dependencies using the command above.
<li>Run the loan_approval_prediction.ipynb notebook to preprocess the data, train the <li>models, and evaluate their performance.
<li>To predict loan approval for new applicants, update the input data in the notebook and <li>rerun the prediction cells.
</ol>

