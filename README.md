# IITM-Project
This repository contains a machine learning project aimed at predicting whether a client will subscribe to a term deposit based on data from direct marketing campaigns of a banking institution. The project is based on a Kaggle competition dataset, and the marketing campaigns were conducted via phone calls. This was a course project for Machine Learning Practice at IIT Madras BS Degree.

# Dataset Description
The dataset contains information collected from previous marketing campaigns. It is divided into training and test sets:

- train.csv: Training dataset used to build the predictive model.
- test.csv: Test dataset used for evaluation.

# Input Variables
The dataset includes the following features:
<br />last_contact_date: Date of the last contact during the campaign.
<br />age: Age of the client (numeric).
<br />job: Type of job (categorical).
<br />marital: Marital status (categorical: "married", "divorced", "single").
<br />education: Education level (categorical: "unknown", "secondary", "primary", "tertiary").
<br />default: Has credit in default? (binary: "yes", "no").
<br />balance: Average yearly balance in euros (numeric).
<br />housing: Has a housing loan? (binary: "yes", "no").
<br />loan: Has a personal loan? (binary: "yes", "no").
<br />contact: Contact communication type (categorical: "unknown", "telephone", "cellular").
<br />duration: Last contact duration in seconds (numeric).
<br />campaign: Number of contacts performed during this campaign (numeric).
<br />pdays: Days since the client was last contacted (-1 if not previously contacted).
<br />previous: Number of contacts before this campaign (numeric).
<br />poutcome: Outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success").
# Target Variable
target: Whether the client subscribed to a term deposit (yes or no).

## Approach  
The project follows these key steps:  

1. **Data Cleaning and Preprocessing**: 
2. **Exploratory Data Analysis (EDA)**:  
3. **Modeling**:  
4. **Evaluation**:  
   - Measured performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.  

## Best Score
0.758

