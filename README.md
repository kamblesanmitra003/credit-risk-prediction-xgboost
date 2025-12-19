# Credit Risk Prediction using XGBoost
This project presents a machine learning–based Credit Risk Prediction system that classifies loan applicants as either Good or Bad credit risks. Among several classification models evaluated, XGBoost (XGB) was selected as the final model due to its superior predictive performance.

The trained model is deployed through a Streamlit web application, allowing users to enter applicant details and receive real-time predictions.

🚀 Key Features

Predicts Good or Bad Credit Risk
Implements XGBoost, the top-performing model among tested algorithms
Interactive Streamlit interface for user inputs
Handles categorical variables using label encoding
Provides real-time predictions using a trained ML model

Machine Learning Approach
Models Evaluated
During experimentation, multiple algorithms were trained and assessed, including:
Decision Tree
Random Forest
Extra Trees Classifier
XGBoost
XGBoost was chosen for the final model due to:
Higher predictive accuracy
Robust handling of non-linear relationships
Consistently strong performance across datasets

Prediction Output

The model classifies applicants into:

Prediction	Meaning
Good Credit Risk	Low likelihood of loan default
Bad Credit Risk	Higher likelihood of loan default
🖥 Web Application

The Streamlit app allows users to input key applicant details, including:

Age
Sex
Job type
Housing status
Saving account status
Checking account status
Credit amount
Loan duration (months)
The app uses the trained XGBoost model to provide instant credit risk predictions based on these inputs.

🛠️ Tech Stack

Python
Pandas
Scikit-learn
XGBoost
Streamlit
Joblib
Dataset

The dataset includes applicant demographic and financial information, such as age, employment status, housing, account balances, credit amount, and loan duration.

Note: This project is for educational purposes and demonstration only. It should not be used for real-world financial decisions without thorough validation.

📈 Future Enhancements

Visualize feature importance
Display model confidence/probabilities
Enhance UI/UX with charts and explanations
Deploy on Streamlit Cloud or other platforms

👨‍💻 Author
Sanmitra Kamble
