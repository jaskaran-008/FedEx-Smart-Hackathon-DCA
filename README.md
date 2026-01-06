# 🚀 FedEx Smart Hackathon 2025  
## 📦 Debt Collection Agency (DCA) Automation System

---

## 🧠 Project Overview
This repository contains a **prototype solution** developed for the **FedEx Smart Hackathon 2025**.  
The project focuses on automating and improving the **Debt Collection Agency (DCA)** workflow using data analytics and machine learning.

The goal is to replace manual, slow processes with a **centralized, data-driven system**.

---

## 🎯 Problem Statement
FedEx Smart Center collaborates with multiple external DCAs to recover overdue loans.  
The existing process is largely manual, resulting in:

- ❌ Delayed case prioritization  
- ❌ Lack of centralized visibility  
- ❌ Inefficient recovery operations  

---

## 💡 Solution Approach
This project demonstrates how automation can help by:

- ✅ Prioritizing overdue loan cases
- ✅ Simulating DCA assignment and case status tracking
- ✅ Providing analytical dashboards for insights
- ✅ Using machine learning to understand default drivers

The solution is designed as a **learning-focused prototype**, not a production system.

---

## 🔄 System Pipeline
1. Load and inspect loan data  
2. Clean and preprocess features  
3. Engineer operational attributes (days overdue, priority)  
4. Simulate DCA case handling  
5. Visualize key trends and distributions  
6. Train and evaluate a machine learning model  
7. Interpret results using feature importance  

---

## 🤖 Machine Learning
- **Model Used:** Decision Tree Classifier  
- **Purpose:** Interpretability and understanding risk drivers  
- **Accuracy Achieved:** ~86%

A Random Forest model was evaluated for comparison but was not retained due to negligible improvement.

---

## 📊 Key Insights
- Loan burden relative to income is the strongest risk indicator  
- Interest rate and income significantly influence defaults  
- Operational features (days overdue) are crucial for workflow prioritization  

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook (VS Code)

---

## 📁 Repository Structure
- dca.ipynb # Complete analysis & modeling notebook
-  README.md # Project documentation
- credit_risk_dataset.csv (data) # Dataset 

## 🏁 Conclusion
- This project showcases how data analytics and machine learning can streamline debt collection operations.  
- It aligns with FedEx Smart Hackathon objectives and serves as a strong foundation for further enhancements.

## 📌 Note

This repository is created strictly for **hackathon submission and learning purposes**.
