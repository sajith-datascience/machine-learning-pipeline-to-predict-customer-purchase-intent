# machine-learning-pipeline-to-predict-customer-purchase-intent
# Online Shoppers Purchase Intention Prediction

## 📌 Project Overview
This project focuses on predicting whether an online shopper will make a purchase during a browsing session using the **Online Shoppers Intention dataset**. The goal is to build an end-to-end machine learning pipeline that handles preprocessing, class imbalance, feature selection, and model evaluation effectively.

---

## 📊 Dataset
- **Dataset**: Online Shoppers Intention Dataset  
- **Source**: UCI Machine Learning Repository  
- **Description**:  
  The dataset contains session-level data capturing user behavior such as page visits, session duration, bounce rates, traffic type, and more.  
- **Target Variable**: `Revenue`  
  - `1` → Purchase made  
  - `0` → No purchase  

---

## 🛠️ Tech Stack & Tools
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Imbalanced-learn (SMOTE)    

---

## 🔄 Project Workflow
1. Data cleaning and preprocessing  
2. Separation of numerical and categorical features  
3. Feature scaling and encoding using pipelines  
4. Handling class imbalance using **SMOTE**  
5. Feature selection with **SelectKBest**  
6. Model comparison using cross-validation  
7. Performance evaluation using ROC-AUC, Accuracy, Precision, Recall, and F1-score  

---

## 🤖 Models Evaluated
- Dummy Classifier  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- Support Vector Machine (SVC)  
- Multi-Layer Perceptron (MLP)  

Each model was evaluated using **10-fold cross-validation** with ROC-AUC as the primary metric.

---

## 📈 Results
- **Accuracy**: ~88%  
- **ROC-AUC**: ~0.84  
- **F1-score (Purchase class)**: ~0.66  

### Key Observations:
- The model accurately predicts **non-purchasing users** with high precision.
- It successfully identifies a majority of **purchasing customers**, showing strong recall for the positive class.
- Overall results demonstrate that consumer behavior data can be effectively used to predict purchase intention.

---

## ✅ Conclusion
The project shows that purchase intention can be predicted with a good degree of accuracy using session-based behavioral data. While there is room for improvement—particularly in increasing precision for purchasing users—the model provides a strong baseline for real-world business applications such as targeted marketing and conversion optimization.

---

## 🚀 Future Improvements
- Hyperparameter tuning for top-performing models  
- Trying advanced ensemble methods  
- Cost-sensitive learning for better handling of false positives  
- Deployment as a web application or API  

---


---

## 🙌 Acknowledgements
- UCI Machine Learning Repository  
- Scikit-learn and Imbalanced-learn documentation  

---

## 📬 Contact
Feel free to connect with me for feedback, collaboration, or discussion.

