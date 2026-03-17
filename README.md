# Predictive-Analytics-Lab-Exam-2
Second Lab Examination: Predictive Analytics
Primary Goal
The central aim  is to construct a machine learning classification algorithm capable of forecasting the correct target category based on the provided data.

Data Description
The dataset designated for this project consists of two independent variables and a single binary dependent variable.

Predictors (Inputs):

Feature 1

Feature 2

Labels (Target):

Yes

No

Initial Data Exploration (EDA)
To better comprehend the underlying patterns and makeup of the data, an exploratory analysis was conducted through the following procedures:

Evaluating the overall shape and structural dimensions of the dataset.

Scanning the data for any missing or null values.

Graphing the frequency of the target classes using a count plot.
<img width="791" height="623" alt="image" src="https://github.com/user-attachments/assets/b8b117e9-5a76-4434-a09b-3f6f3bff7e17" />


Mapping the correlation between Feature 1 and Feature 2 utilizing a scatter plot.
<img width="715" height="537" alt="image" src="https://github.com/user-attachments/assets/4889d409-6fc9-4a9b-9611-283f6d62a5c0" />

Data Preparation
Prior to model training, the raw data underwent several preprocessing steps:

Encoding the categorical target labels ("Yes" / "No") into a machine-readable binary format (1 / 0).

Assessing the class frequencies to detect any potential data imbalance.
<img width="754" height="590" alt="image" src="https://github.com/user-attachments/assets/dfd2e787-1b30-492a-b221-f82543742ebc" />


Partitioning the dataset into distinct subsets for model training and subsequent testing.

Model Construction
A Logistic Regression classifier was deployed to train on the prepared data, capturing the mathematical relationship between the independent input features and the predicted outcomes.

Visualizing the Decision Boundary
A chart was generated to graphically display the model's decision threshold, illustrating exactly how the trained algorithm divides the two categories across the two-dimensional feature space.
<img width="727" height="629" alt="image" src="https://github.com/user-attachments/assets/6df0355b-ba02-4645-8b04-9edec23cda68" />

Performance Assessment
The classifier's predictive capabilities and overall reliability were measured utilizing the following metrics:

Overall Accuracy Metric

Confusion Matrix

Comprehensive Classification Report (detailing Precision, Recall, and F1-Score)
<img width="671" height="323" alt="image" src="https://github.com/user-attachments/assets/d56bbcef-342c-4cf4-9131-f9aa243d37bb" />

Technologies and Frameworks Implemented
Python

Pandas

Matplotlib

Seaborn

Scikit-learn
