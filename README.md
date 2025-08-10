# Netflix-ML-Project
Machine Learning project on Netflix dataset with EDA and model building

****Netflix Machine Learning Project****

📌 **Project Overview**

This project focuses on building and evaluating multiple machine learning models to predict outcomes based on Netflix-related data.
The goal is to determine the most suitable model for achieving a positive business impact through accurate and reliable predictions.

The project workflow includes:

Data preprocessing & exploratory data analysis (EDA)

Model building & training

Hyperparameter tuning

Evaluation based on selected metrics

Model explainability using SHAP feature importance

📂 **Dataset**

The dataset used contains Netflix-related features such as title information, content ratings, genres, and other relevant metadata.
Data preprocessing included:

Handling missing values

Encoding categorical variables

Feature scaling where required

Train-test splitting

🛠 **Machine Learning Models Used**

Three ML models were implemented and compared:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Each model was tuned using RandomizedSearchCV to find optimal hyperparameters.

📊 **Evaluation Metrics**

The following metrics were considered for business impact:

Accuracy – To measure the overall correctness of the model predictions

Precision & Recall – To ensure relevant results are prioritized while minimizing false positives/negatives

F1 Score – To maintain a balance between precision and recall

ROC-AUC Score – To assess the model’s ability to distinguish between classes

✅ **Final Model Selection**

The XGBoost Classifier was chosen as the final prediction model because:

It provided the highest F1 Score and ROC-AUC score among all models

It showed strong generalization capabilities on the test set

It effectively handled feature interactions and non-linear relationships

🔍 **Model Explainability**

To interpret the predictions, SHAP (SHapley Additive exPlanations) was used for feature importance analysis.
Key insights from SHAP:

Certain features (e.g., content rating, release year, and genre) had a higher influence on predictions

The visualization helped in understanding the model’s decision-making process, making it more transparent for business stakeholders

📦 **Requirements**

Install the dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
Main libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost

shap

🚀 **How to Run**

Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/netflix-ml-project.git
Navigate to the project folder:

bash
Copy
Edit
cd netflix-ml-project
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Netflix_ML_Project_Junaid_Kamate.ipynb
Run all cells to execute the full pipeline.

📌 **Conclusion**

The XGBoost Classifier emerged as the best-performing model for predicting outcomes from Netflix data, balancing accuracy with interpretability.
The project demonstrates the importance of careful model selection, hyperparameter tuning, and explainability for building trust in ML solutions.
Future improvements could involve experimenting with deep learning models or expanding the dataset for richer predictions.


