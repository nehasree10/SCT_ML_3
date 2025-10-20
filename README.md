# 🌳 Decision Tree Classifier on Bank Marketing Dataset

## 📘 Overview
This project implements a **Decision Tree Classifier** to predict whether a customer will **subscribe to a term deposit** based on the **Bank Marketing dataset** from the UCI Machine Learning Repository.  
The model uses demographic and marketing-related features to make predictions, demonstrating the use of tree-based models for classification tasks.

---

## 🧠 Key Features
- Extracts nested ZIP files and loads dataset dynamically  
- Encodes categorical features using **LabelEncoder**  
- Splits data into training and testing sets  
- Builds and evaluates a **Decision Tree Classifier**  
- Visualizes the trained decision tree  
- Generates performance metrics like accuracy and classification report  

---

## 🧩 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## 📂 Dataset
The dataset used is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

**Dataset Files:**
- `bank+marketing.zip` (outer ZIP)  
  └── `bank-additional.zip` (inner ZIP)  
      └── `bank-additional-full.csv` — the main dataset file  

**Key Features:**
- `age` — Customer’s age  
- `job`, `marital`, `education` — Socio-demographic attributes  
- `balance` — Account balance  
- `housing`, `loan` — Loan status  
- `contact`, `month`, `day_of_week` — Contact details  
- `duration` — Last contact duration  
- `campaign` — Number of contacts during this campaign  
- `pdays`, `previous` — Past campaign performance  
- `poutcome` — Outcome of the previous campaign  

**Target Variable:**
- `y` — Whether the client subscribed to a term deposit (`yes` or `no`)

---

## ⚙️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/bank-marketing-decision-tree.git
cd bank-marketing-decision-tree
# SCT_ML_3
