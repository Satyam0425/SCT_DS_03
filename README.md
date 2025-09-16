# 📊 Customer Purchase Prediction using Decision Tree Classifier  

This project implements a **Decision Tree Classifier** to predict whether a customer will subscribe to a **term deposit** (bank product/service) based on their **demographic, behavioral, and economic data**.  
The dataset used is the **Bank Marketing dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).  

---

## 📁 Dataset  
- **File:** `bank-additional-full.csv`  
- **Source:** [Moro et al., 2014, Decision Support Systems](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- **Size:** 41,188 instances, 20 input attributes, and 1 output attribute (`y`)  

**Target Variable:**  
- `y = yes` → customer subscribed  
- `y = no` → customer did not subscribe  

---

## ⚙️ Project Workflow  
1. **Data Loading** – Import dataset in Google Colab and explore it  
2. **Preprocessing** –  
   - Drop `duration` (to avoid data leakage)  
   - One-hot encode categorical variables  
   - Convert target (`y`) into binary (Yes=1, No=0)  
3. **Model Building** – Train a Decision Tree Classifier  
4. **Evaluation** – Accuracy, Confusion Matrix, Classification Report  
5. **Visualization** – Decision tree plot and feature importance  

---

## 🛠️ Tech Stack  
- Python 🐍  
- pandas, NumPy  
- scikit-learn  
- matplotlib  
- Google Colab / Jupyter Notebook  

---

## 🚀 How to Run  

Clone the repository:  
```bash
decisiontree.ipynb
##cd bank-marketing-decision-tree
