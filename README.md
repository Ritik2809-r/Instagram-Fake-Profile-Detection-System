# Instagram Fake Profile Detection System

## 📌 Overview
The **Instagram Fake Profile Detection System** is a machine learning–based project designed to automatically identify fake or suspicious Instagram accounts. The system analyzes profile attributes, behavioral patterns, and network indicators to classify accounts as **Fake** or **Genuine**.

This project helps reduce online scams, impersonation, misinformation, and bot-driven activities on social media platforms.

---

## ❓ Problem Statement
With the rapid growth of Instagram users, fake and bot profiles have increased significantly. Manual detection is slow, inconsistent, and unable to scale. There is a strong need for an **automated, accurate, and intelligent detection system** that can identify fake profiles efficiently.

---

## 🎯 Objectives
- Detect fake Instagram profiles using machine learning  
- Analyze profile, behavioral, and engagement-based features  
- Compare Decision Tree and Random Forest models  
- Improve detection accuracy using ensemble learning  
- Explain predictions using Explainable AI (SHAP)  
- Deploy the model using a Streamlit web interface  

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Explainable AI:** SHAP  
- **Model Deployment:** Streamlit  
- **Tools:** Jupyter Notebook  

---

## 📊 Dataset & Features
The dataset contains Instagram profile attributes commonly associated with fake accounts.

**Key Features:**
- Profile picture presence  
- Followers count  
- Following count  
- Number of posts  
- Bio length and content  
- Username patterns  
- Engagement metrics (likes, comments)  

These features capture both **behavioral patterns** and **profile authenticity indicators**.

---

## 🔍 Data Preprocessing & EDA
- Handled missing and inconsistent values  
- Cleaned irregular entries  
- Normalized numerical features  
- Encoded categorical variables  
- Performed Exploratory Data Analysis (EDA) to identify trends and correlations  

---

## 🤖 Machine Learning Models Used

### 1️⃣ Decision Tree Classifier
- Simple and interpretable  
- Learns rule-based decisions  
- Prone to overfitting on complex data  

### 2️⃣ Random Forest Classifier
- Ensemble of multiple decision trees  
- Reduces overfitting  
- Handles complex feature interactions  
- Provides feature importance  

✅ **Random Forest performed best and was selected as the final model.**

---

## 📈 Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

**Random Forest Results:**
- Accuracy: ~93–94%  
- Precision: High  
- Recall: High  
- ROC-AUC: ~0.94  

---

## 🔎 Explainable AI (XAI) using SHAP
To ensure transparency and trust:
- SHAP values were used to explain model predictions  
- Identified the most influential features  
- Validated that the model makes meaningful decisions  

---

## 🚀 Deployment (Streamlit)
The trained model was deployed using **Streamlit**, allowing users to:
- Enter Instagram profile details  
- Instantly predict whether a profile is **Fake** or **Genuine**  
- View results in a simple, interactive interface  

---

## 📂 Project Structure

Instagram-Fake-Profile-Detection-System/
│── data/
│── notebooks/
│── models/
│── app/
│── reports/
│── requirements.txt
│── README.md


---

## 🔮 Future Enhancements
- Deep learning models (CNN, LSTM, BERT, GNN)  
- Real-time profile monitoring  
- Deepfake profile detection  
- Explainable AI dashboards  
- Cloud-based deployment  

---

## 👥 Team Members
- Aakriti Arora  
- Akanksha Sinha  
- Manas Arora  
- Harshit Pandey  
- Aakriti Jha  
- **Ritik Raushan**

---

## 👨‍💻 Author
**Ritik Raushan**  
Department of Information Technology  
KIIT University, Bhubaneswar

---

⭐ If you found this project useful, please star the repository!
