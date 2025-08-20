# 💳 Loan Default Risk Prediction  

This project builds a **machine learning pipeline** to predict the likelihood of loan defaults, using a German credit dataset.  
It was developed as part of the **Introduction to Machine Learning** course at the University of Arizona.  

---

## 🎯 Objectives  
- Predict **loan default risk** to help financial institutions reduce credit exposure.  
- Explore and preprocess real-world banking datasets.  
- Compare multiple machine learning models to balance accuracy and interpretability.  

---

## 🗂️ Project Structure  
```
Loan_Default_Risk_Prediction-main/
│── Context.txt             # Project description and dataset context
│── Final.ipynb             # Jupyter Notebook with full implementation
│── Final.html              # Rendered notebook (HTML)
│── Final Project.pdf       # Final report
│── README.md               # Project overview (this file)
```

---

## ⚙️ Tools & Libraries  
- **Python**  
- **Data Handling:** pandas, NumPy  
- **Machine Learning:** scikit-learn (Logistic Regression, Random Forest, Gradient Boosting, SVM)  
- **Visualization:** matplotlib, seaborn  
- **Notebook:** Jupyter  

---

## 🔍 Methods  
1. **Data Preprocessing**  
   - Imputed missing values with column means.  
   - Encoded categorical variables for ML compatibility.  
   - Standardized numerical features for uniform scaling.  

2. **Model Development**  
   - Implemented **Logistic Regression, Random Forest, Gradient Boosting, and Support Vector Machine (SVM)**.  
   - Tuned hyperparameters (grid/random search) for performance optimization.  

3. **Evaluation**  
   - Compared models on **Accuracy, Precision, Recall, and F1-score**.  
   - Assessed trade-offs between interpretability and predictive power.  

---

## 📈 Key Findings  
- **Tree-based ensemble methods (Random Forest, Gradient Boosting)** outperformed simpler models in accuracy.  
- **Logistic Regression** provided transparency and interpretability of financial risk drivers.  
- Preprocessing steps like encoding and scaling significantly improved model performance.  

---

## 📜 Deliverables  
- **Jupyter Notebook** with full ML pipeline (`Final.ipynb`)  
- **Final Report (PDF)** with results and discussion  
- **HTML Export** of the notebook  

---

## 👩‍💻 Author  
- **Rohit Surya** — End-to-end implementation (data wrangling, modeling, evaluation, reporting)  

---

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/loan-default-risk-prediction.git
   cd Loan_Default_Risk_Prediction-main
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Open Jupyter Notebook and run:  
   ```bash
   jupyter notebook Final.ipynb
   ```  

---

## 📌 License  
This project is for academic purposes (University of Arizona, Intro to Machine Learning).  
