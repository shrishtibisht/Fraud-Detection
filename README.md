# 💳 Credit Card Fraud Detection with Machine Learning  

## 📌 Project Overview  
Fraudulent transactions cost financial institutions **billions annually**.  
This project applies **Machine Learning** to detect credit card fraud using real transaction data, where fraud cases are extremely rare (only **0.17% of the dataset**).  

The main objective is to build models that:  
- Accurately **detect fraudulent transactions**  
- Handle **class imbalance** effectively  
- Provide **business value** by reducing financial risks and protecting customers  

---

## 📂 Dataset  
- **Source:** [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Size:** 284,807 transactions, ~150 MB  
- **Note:** Due to large file size, the dataset is **not uploaded to this repo**.  
  🔗 Please download it directly from Kaggle.  

---

## ⚙️ Methodology  

### 🔄 Data Preprocessing  
- Handled **class imbalance** using **SMOTE (Synthetic Minority Oversampling Technique)**  
- Scaled features using **StandardScaler**  
- Train-test split with **stratification**  

### 🤖 Models Implemented  
- **Logistic Regression** – simple, interpretable baseline  
- **Random Forest** – ensemble learning for higher recall & precision  

### 📊 Evaluation Metrics  
- **Confusion Matrix**  
- **Precision, Recall, F1-Score**  
- **ROC-AUC Score**  

---

## 📈 Results  

### Logistic Regression  
- ROC-AUC: **0.94**  
- Recall (Fraud class): **0.90**  

### Random Forest  
- ROC-AUC: **0.98**  
- Recall (Fraud class): **0.87**  
- Precision (Fraud class): **0.62**  

✅ **Random Forest outperformed Logistic Regression** with a better balance of precision & recall, making it more reliable for fraud detection.  

---

## 💡 Business Impact  
- Early detection of fraudulent transactions → **reduced financial losses**  
- Protects customer trust & ensures **regulatory compliance**  
- Supports **fraud investigation teams** with actionable insights  

---

## 📌 Repository Structure  

```bash
📁 Credit-Card-Fraud-Detection
│── 📓 fraud_detection_nb.ipynb   # Jupyter Notebook with full pipeline
│── 📄 README.md                  # Project documentation (this file)
