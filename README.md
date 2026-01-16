# IITM-Project
This repository contains a machine learning project aimed at predicting whether a client will subscribe to a term deposit based on data from direct marketing campaigns of a banking institution. The project is based on a Kaggle competition dataset, and the marketing campaigns were conducted via phone calls. This was a course project for Machine Learning Practice at IIT Madras BS Degree.

Dataset Description
The dataset contains information collected from previous marketing campaigns. It is divided into training and test sets:

train.csv: Training dataset used to build the predictive model.
test.csv: Test dataset used for evaluation.
sample_submission.csv: Sample output file format for predictions.

Input Variables
The dataset includes the following features:

last_contact_date: Date of the last contact during the campaign.
age: Age of the client (numeric).
job: Type of job (categorical).
marital: Marital status (categorical: "married", "divorced", "single").
education: Education level (categorical: "unknown", "secondary", "primary", "tertiary").
default: Has credit in default? (binary: "yes", "no").
balance: Average yearly balance in euros (numeric).
housing: Has a housing loan? (binary: "yes", "no").
loan: Has a personal loan? (binary: "yes", "no").
contact: Contact communication type (categorical: "unknown", "telephone", "cellular").
duration: Last contact duration in seconds (numeric).
campaign: Number of contacts performed during this campaign (numeric).
pdays: Days since the client was last contacted (-1 if not previously contacted).
previous: Number of contacts before this campaign (numeric).
poutcome: Outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success").
Target Variable
target: Whether the client subscribed to a term deposit (yes or no).

