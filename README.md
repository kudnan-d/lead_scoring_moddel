
# 📊 Lead Scoring Case Study  

## Objective  
X Education, an online course provider, struggles with a **low lead conversion rate (~30%)**. The goal is to **build a Logistic Regression model** that assigns a **Lead Score (0-100)** to prioritize **high-potential leads (Hot Leads)** and improve conversions.  

---

## Steps Followed  

### 1. **Data Preparation**  
- Read and clean **Leads.csv** dataset.  
- Handle missing values and preprocess data.  
- Perform **Exploratory Data Analysis (EDA)**.  

### 2. **Feature Engineering**  
- Create **dummy variables** for categorical features.  
- Split data into **training & test sets**.  

### 3. **Model Building & Optimization**  
- Train a **Logistic Regression Model**.  
- Optimize features using **Recursive Feature Elimination (RFE)**.  
- Check for **multicollinearity (VIF analysis)**.  

### 4 **Model Evaluation**  
- **Predictions** on test data.  
- **Performance Metrics:**  
  - **ROC Curve & AUC Score**  
  - **Precision-Recall Curve**  
  - **Confusion Matrix & Accuracy**  

---

## 📂 Project Structure  
```
📁  Lead-Scoring-Case-Study
│── 📜 Lead_Scoring_Model_LR.ipynb          # Python Notebook (Model & Analysis)
│── 📜 Assignment Subjective Questions.pdf  # Business Problem Responses
│── 📜 Lead_Score_Case_Study.pdf            # Final Presentation
│── 📜 Leads.csv                            # Raw Dataset
│── 📜 Leads_Data_Dictionary.xlsx           # Data Dictionary
│── 📜 Lead Scoring CS Summary.pdf          # Project Summary
│── 📜 requirements.txt                     # Required Libraries
│── 📜 README.md                            # Project Overview (You are here)
```

---

## Deliverables  
**Lead Scoring Model** (Predicts likelihood of conversion).  
**Business Insights & Recommendations PPT**.  
**Complete Code & Documentation**.  

---

## 🔧 Setup & Installation  
1. Clone this repository:  
```
git clone https://github.com/your-repo/Lead-Scoring-Case-Study.git
cd Lead-Scoring-Case-Study
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3.Open and run the Jupyter Notebook:
```
jupyter notebook Lead_Score_Case_Study.ipynb
```
