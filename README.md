# 📱 Spam SMS Detection (Task 2 – CodSoft Internship)

This project is part of my **Machine Learning Internship at CodSoft**, where I developed a classification model that identifies whether a given SMS message is **spam** or **ham** (not spam).

---

## 📂 Dataset

- **Source**: [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- The dataset contains 5,572 labeled SMS messages.
- Two columns:
  - `v1`: Label (ham/spam)
  - `v2`: Message text

---

## 🚀 Objective

Build and evaluate a machine learning model that can accurately classify SMS messages as spam or not spam using Natural Language Processing (NLP) techniques.

---

## 🧰 Technologies Used

- Python 3
- pandas, NumPy
- scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes
- Jupyter Notebook (in VS Code)

---

## 🔧 Workflow

1. 📥 Load & clean the dataset  
2. 🧹 Preprocess and encode labels (`ham` → 0, `spam` → 1)  
3. ✍️ Convert messages into numeric features using **TF-IDF**  
4. 🤖 Train a **Multinomial Naive Bayes** classifier  
5. 📊 Evaluate performance with:
   - Accuracy
   - Classification report
   - Confusion matrix

---

## 📊 Results

- Achieved high accuracy in detecting spam messages.
- Model performs well with short-form text classification using TF-IDF + Naive Bayes.

---

## 🗂 File Structure
📁 CODSOFT/
├── spam_sms_detection.ipynb
├── README.md
├── requirements.txt
├── spam.csv
└── spam_classifier_model.pkl
