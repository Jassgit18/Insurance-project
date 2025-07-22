# 🛡️ Insurance Claim Prediction

This project focuses on building a machine learning model to predict whether a person is likely to file an insurance claim based on demographic and lifestyle features such as age, sex, BMI, number of children, smoking status, region, and annual medical charges.

---

## 📊 Dataset Overview

The dataset contains **1,338** records with the following features:

| Feature        | Description                                         |
|----------------|-----------------------------------------------------|
| `age`          | Age of the individual                               |
| `sex`          | Gender (0 = female, 1 = male)                        |
| `bmi`          | Body Mass Index                                     |
| `children`     | Number of children/dependents                       |
| `smoker`       | Smoking status (0 = non-smoker, 1 = smoker)         |
| `region`       | Residential region (0 = northeast, 1 = northwest, 2 = southeast, 3 = southwest) |
| `charges`      | Annual medical insurance charges                    |
| `insuranceclaim` | Target variable (0 = no claim, 1 = claim filed)    |

---

## 🎯 Project Goal

The primary goal is to predict the likelihood of an individual filing an insurance claim based on their personal and medical profile. This classification problem can help insurance companies assess risk and develop personalized policies.

---

## 🛠️ Technologies Used

- Python 3.9+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook (optional)

---


---

## 📈 Workflow

1. **Data Preprocessing**
   - Encoding categorical variables (sex, smoker, region)
   - Feature scaling (if necessary)

2. **Exploratory Data Analysis**
   - Distribution of charges, claims, and other features
   - Correlation analysis

3. **Modeling**
   - Logistic Regression / Random Forest / XGBoost
   - Train/test split and cross-validation

4. **Evaluation**
   - Accuracy, precision, recall, F1-score
   - ROC-AUC Curve

5. **Deployment (Optional)**
   - Flask/Streamlit app to interact with the model

---

## 📊 Sample Visualization

![Sample Plot](assets/correlation_heatmap.png)

---

## 🧪 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/your-username/insurance-claim-prediction.git
cd insurance-claim-prediction

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run analysis
jupyter notebook notebooks/analysis.ipynb
