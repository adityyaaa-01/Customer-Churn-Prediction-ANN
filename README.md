# Customer Churn Prediction using Artificial Neural Network (ANN)

## 📌Project Overview
This project implements an **Artificial Neural Network (ANN)** to predict **customer churn** for a bank.  
Customer churn refers to when customers stop doing business with a company.  
By predicting churn, businesses can take proactive measures to retain customers.

The ANN is built using **TensorFlow** and **Keras**, with data preprocessing, training, and evaluation steps.

---

## 📂 Dataset
- **Name:** Churn_Modelling.csv
- **Target:** `Exited` column (1 = Customer left, 0 = Customer stayed)  

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  
- Seaborn  

---

## 📊 Steps Performed
1. **Data Loading & Exploration** – Loaded dataset, checked structure, and analyzed target distribution.  
2. **Data Preprocessing** –  
   - Removed unnecessary columns (`RowNumber`, `CustomerId`, `Surname`,`Geography`,`Gender`)    
   - Scaled features for better ANN performance  
3. **Train-Test Split** – Split dataset into training and testing sets.  
4. **Model Building (ANN)** –  
   - Input layer: Number of neurons = number of features  
   - Hidden layers: Dense layers with ReLU activation  
   - Output layer: Sigmoid activation for binary classification  
5. **Model Compilation & Training** – Optimizer: Adam, Loss: Binary Crossentropy, Metrics: Accuracy  
6. **Model Evaluation** –  
   - Accuracy score    
7. **Prediction on New Data** – Tested ANN with new hypothetical customer data.

---

## 📈 Results
- **Training Accuracy:** 85.675%  
- **Test Accuracy:** 85.6%     

---

## 📚 Key Learnings
- How to preprocess categorical and numerical data for ANN  
- How to design and train a binary classification ANN  
- How activation functions (ReLU, Sigmoid) work in ANN  
- How to evaluate model performance with accuracy, precision, recall, and F1-score  

---

## 🚀 How to Run
1. Clone the repository:  
 ```bash
 git clone https://github.com/yourusername/Customer-Churn-ANN.git
