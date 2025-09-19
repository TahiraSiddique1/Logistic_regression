# 🏦 Banking Data Analysis & Prediction  

This project explores a **bank marketing dataset** using **Python (pandas, matplotlib, seaborn, scikit-learn)**.  
It includes **data cleaning, exploratory analysis, preprocessing, machine learning modeling, and correlation insights**.  

The goal is to understand how different features influence whether a customer subscribes to a term deposit (`y`) and to build a **predictive logistic regression model**.  

---

## ✨ Features  

✅ **Data Exploration**  
- Loaded `banking.csv` dataset into pandas DataFrame  
- Explored dataset structure and target variable distribution  

✅ **Visualizations**  
- Bar plots showing how subscription (`y`) varies across:  
  - Job types  
  - Marital status  
  - Loan status  
  - Previous marketing outcomes (`poutcome`)  

✅ **Preprocessing**  
- Handled categorical features with **dummy variables** (`pd.get_dummies`)  
- Prepared dataset for machine learning  

✅ **Machine Learning Model**  
- Split dataset into training & testing sets  
- Trained a **Logistic Regression model**  
- Achieved **81% accuracy** using `age` as a predictive feature  

✅ **Correlation Analysis**  
- Generated correlation matrix for numerical features  
- Visualized with **seaborn heatmap** to reveal relationships  

---

## 🛠️ Tech Stack  

- **Python** 🐍  
- **Libraries:**  
  - pandas  
  - matplotlib  
  - seaborn  
  - scikit-learn  

---

## 🚀 Getting Started  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/banking-data-analysis.git
cd banking-data-analysis
2. Install dependencies
pip install -r requirements.txt

3. Run the notebook / script

Open Jupyter Notebook:

jupyter notebook banking_analysis.ipynb


Or run Python script:

python banking_analysis.py

###📊 Sample Outputs
Target Distribution by Job

(Example visualization from project)


Correlation Heatmap

**###🎯 Insights**

Certain job types and marital statuses show higher/lower subscription rates.

Loan status and past marketing outcomes significantly influence predictions.

Age alone yields ~81% accuracy, but combining multiple features can further improve performance.



