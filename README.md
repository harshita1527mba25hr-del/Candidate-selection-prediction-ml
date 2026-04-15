 Candidate Selection Prediction using Decision Tree
 Project Overview
This project focuses on building a Machine Learning model to predict whether a candidate will be selected during the recruitment process. The model uses a Decision Tree Classifier to evaluate important factors like experience, test scores, interview performance, and skill match.
The aim is to simulate a smart hiring system that assists HR teams in making efficient and data-driven recruitment decisions.

 Objectives
Generate a synthetic recruitment dataset
Analyze key factors influencing hiring decisions
Train a Decision Tree model for classification
Predict candidate selection outcomes
Apply ML concepts to HR and recruitment scenarios

 Problem Statement
Recruitment processes can be:
Time-consuming
Subjective
Inconsistent
This project helps answer:
 "Will the candidate be selected or rejected?"

 Dataset Description
The dataset is randomly generated and includes the following features:
Feature Name
Description
experience_years
Candidate's years of experience
test_score
Score in written/technical test
interview_score
Score in interview
skill_match
Skill alignment (1 = Low, 2 = Medium, 3 = High)
selected
Target variable (1 = Selected, 0 = Rejected)


 Working Process
Step 1: Data Generation
Synthetic dataset created using NumPy
Simulates real-world recruitment scenarios
Step 2: Target Logic
Candidate is selected when:
Experience ≥ 3 years AND test & interview scores ≥ 60
OR high skill match with strong interview performance
Step 3: Model Training
Algorithm: Decision Tree Classifier
Learns patterns from candidate data
Step 4: Prediction
Example input:
[experience_years, test_score, interview_score, skill_match]


Output:
1 → Candidate Likely to be Selected
0 → Candidate Likely to be Rejected

 Sample Output
Prediction Result: 1  
Candidate Likely to be Selected


 Technologies & Tools Used
Python 
Google Colab
Pandas
NumPy
Scikit-learn
Tool Used: This project was developed and executed using Google Colab Notebook for coding, dataset generation, and model training.

 How to Run the Project
Open the notebook in Google Colab / Jupyter Notebook
Run all cells step by step
Observe dataset preview
Train the model
Check prediction results

 Key Learnings
Understanding classification in HR analytics
Decision Tree algorithm implementation
Data-driven hiring decisions
Application of ML in recruitment systems

 Future Enhancements
Use real recruitment datasets
Implement advanced models (Random Forest, XGBoost)
Build HR analytics dashboards
Integrate with Applicant Tracking Systems (ATS)

 Conclusion
This project demonstrates how Machine Learning can assist in automating and improving recruitment decisions, making the hiring process faster, more consistent, and data-driven.

 Author
Harshita
