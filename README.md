<h1>Credit Card Fraud Detection Using Machine Learning</h1>

🧾Summary

✅A machine learning system that identifies fraudulent financial transactions using historical transaction data.

🔍 Overview

✅Fraud costs companies billions every year. Manual rule-based systems fail because fraud patterns change constantly. ✅This project applies machine learning models to automatically learn patterns from transaction data and classify transactions as fraudulent or legitimate.

❓ Problem Statement

✅Financial institutions need to detect fraudulent transactions in real time with high precision.

✅Core challenges:

⚠️ Highly imbalanced dataset (fraud cases are very rare)

⚠️ False positives hurt customer trust

⚠️ False negatives cause direct financial loss

The goal is to build a model that maximizes fraud detection while minimizing false alarms.

📊 Dataset

👉Source:<a href="https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download">Transaction-level financial dataset </a>

✅Rows: Large-scale 

✅Target Variable: is_fraud (0 = Legit, 1 = Fraud)

👉Key Features:

✅Transaction amount

✅Transaction type

✅Time-based features

✅Account / customer attributes

🛠️ Tools & Technologies

👉Programming & Libraries

✅Python, ✅NumPy, ✅Pandas, ✅Matplotlib, ✅Seaborn

👉Machine Learning

✅Scikit-learn, ✅Pipeline & ColumnTransformer, ✅StandardScaler, OneHotEncoder

👉Evaluation

✅Confusion Matrix

✅Precision, Recall, F1-score

✅ROC-AUC

⚙️ Methods / Approach

1️⃣ Data Preprocessing

✅Missing value handling

✅Feature scaling for numerical data

✅One-hot encoding for categorical data

✅Train-test split before scaling (to avoid data leakage)

2️⃣ Handling Imbalance

✅Focus on recall & precision, not accuracy

✅Model evaluation based on confusion matrix

3️⃣ Model Building

✅Logistic Regression

✅Tree-based models (if applied)

✅Pipeline used to avoid preprocessing mistakes

4️⃣ Model Evaluation

✅Confusion matrix analysis

✅Classification report

✅ROC curve

📈 Key Insights

✅Accuracy alone is misleading for fraud detection.

✅A model with 99% accuracy can still miss most fraud cases.

✅Proper preprocessing and evaluation matter more than fancy algorithms.

✅Recall is critical, but precision cannot be ignored.

📊 Dashboard / Model Output

👉Outputs include:

✅Fraud vs Non-Fraud distribution plots

✅Confusion matrix visualization

✅Probability-based predictions

👉If converted into a dashboard, key KPIs would be:

✅Fraud Detection Rate

✅False Positive Rate

✅Transaction Risk Score

▶️ How to Run This Project

1️⃣ Clone the repository

git clone https://github.com/rajan-kumar-mu1439/credit-card-fraud-detection-ml

2️⃣ Install dependencies

pip install ✅Python, ✅NumPy, ✅Pandas, ✅Matplotlib, ✅Seaborn

3️⃣ Open Jupyter Notebook

jupyter notebook

4️⃣ Run Fraud prediction.ipynb

That’s it. No unnecessary complexity.

👉 Results & Conclusion

✅The model successfully identifies fraudulent transactions

✅Performance evaluated using business-relevant metrics

✅Demonstrates a practical ML workflow for real-world fraud problems


🔮 Future Work

✅ Use advanced models (XGBoost, LightGBM)

✅ Apply SMOTE or cost-sensitive learning

✅ Real-time fraud detection pipeline

✅ Deploy as a web dashboard (Streamlit)

✅ Model monitoring & drift detection

👤 Author & Contact

Rajan Kumar

Python Developer | MI & Data Analytics

📧 Email: rajankumarmu1439

🔗 LinkedIn: https://www.linkedin.com/in/rajan-kumar-mu1439/
