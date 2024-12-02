# LOAN APPROVAL PREDICTION


| Column                         | Description                                      | Type        |
|--------------------------------|--------------------------------------------------|-------------|
| person_age                     | Age of the person                                | Float       |
| person_gender                  | Gender of the person                             | Categorical |
| person_education               | Highest education level                          | Categorical |
| person_income                  | Annual income                                    | Float       |
| person_emp_exp                 | Years of employment experience                   | Integer     |
| person_home_ownership          | Home ownership status (e.g., rent, own, mortgage)| Categorical |
| loan_amnt                      | Loan amount requested                            | Float       |
| loan_intent                    | Purpose of the loan                              | Categorical |
| loan_int_rate                  | Loan interest rate                               | Float       |
| loan_percent_income            | Loan amount as a percentage of annual income     | Float       |
| cb_person_cred_hist_length     | Length of credit history in years                | Float       |
| credit_score                   | Credit score of the person                       | Integer     |
| previous_loan_defaults_on_file | Indicator of previous loan defaults              | Categorical |
| loan_status (target variable)  | Loan approval status: 1 = approved; 0 = rejected | Integer     |



Classification Model:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost
5. SVM
6. KNN
7. Naive Bayes
8. AdaBoost
9. Gradient Boosting
10. Neural Network

###Project Type : 
Take a specific problem, pose it as a machine
learning problem (classification, regression, clustering, ..),
train a ML model and study its performance.

###Project implementation would have the following characteristics:
• Pick the dataset from a good online source.
• A good study of the characteristics and properties of the
dataset.
• A decent amount of introductory data analysis done
(correlations, label and feature distributions, missing values,
imbalance, mean/variance of features, etc.)
• A comprehensive evaluation of different ML algorithms
(linear models, decision trees, boosted trees and random
forests, neural networks, etc.)
• Use of meaningful evaluation metrics
• An analysis of what works and what does not work
• Lessons Learnt from the Project and How the project helped
you.


Decision Tree:
- The decision tree algorithm is a supervised learning algorithm that can be used for both classification and regression tasks. It is a tree-like model that makes predictions by recursively partitioning the input space into smaller and smaller regions.
- Stopping Criteria:
  - Maximum Depth: The maximum depth of the tree is a stopping criterion that limits the number of splits in the tree. If the tree reaches the maximum depth, it stops growing.
  - Minimum Samples per Leaf: The minimum number of samples required to form a leaf node is another stopping criterion. If the number of samples in a leaf node falls below this threshold, the tree stops growing.
  - Minimum Samples per Split: The minimum number of samples required to split a node is another stopping criterion. If the number of samples in a node falls below this threshold, the tree stops growing.
  - Impurity Threshold: The impurity threshold is a stopping criterion that specifies the minimum impurity required to split a node. If the impurity of a node falls below this threshold, the tree stops growing.
  - Minimum Information Gain: The minimum information gain required to split a node is a stopping criterion. If the information gain from splitting a node is below this threshold, the tree stops growing.
  - Maximum Number of Leaves: The maximum number of leaves in the tree is a stopping criterion. If the number of leaves exceeds this threshold, the tree stops growing.
  

