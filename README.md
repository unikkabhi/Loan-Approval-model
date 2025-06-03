# 🏦 Loan Approval Prediction Model

A machine learning project that predicts loan approval status based on applicant details. Designed to assist financial institutions in automating and improving the accuracy of loan approval decisions.

## 📊 Dataset

The dataset includes the following features:

- Gender  
- Marital Status  
- Education  
- Applicant Income  
- Loan Amount  
- Credit History  
- Property Area  
- Loan Status (Target)

## ⚙️ Technologies Used

- Python 3.10+
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost / Random Forest
- Jupyter Notebook

## 🚀 Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Scaled numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualized trends and feature relationships

3. **Model Development**
   - Trained and tuned multiple classifiers
   - Evaluated with metrics like Accuracy, Precision, Recall, F1-score

4. **Model Saving**
   - Exported best-performing model using `joblib` or `pickle`

## 📈 Results

- Achieved **~85% accuracy**
- Credit History and Income emerged as key features
- Final model: **XGBoost Classifier**

## ✅ How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/loan-approval-model.git
cd loan-approval-model

# Install dependencies
pip install -r requirements.txt

# Run a Jupyter Notebook
jupyter notebook notebooks/model_training.ipynb
