#  Spam Email Detection using Machine Learning

##  Project Overview

Email spam continues to be a major cybersecurity concern, exposing users to unwanted advertisements, phishing attacks, fraud, and malicious content. The objective of this project is to build an intelligent spam email detection system using Python and Machine Learning that accurately classifies messages as **Spam** or **Ham (Not Spam)**.

This project was developed as part of a Data Science internship and demonstrates the complete machine learning workflow—from data preprocessing to model evaluation and prediction.

---

##  Problem Statement

Spam emails flood inboxes with unsolicited and potentially harmful messages. Traditional filtering techniques often fail to detect newly generated spam patterns.

The goal of this project is to develop a machine learning model capable of automatically identifying spam emails based on their textual content, helping improve email security and user experience.

---

##  Project Objectives

- Clean and preprocess the email dataset.
- Handle missing and duplicate values.
- Convert textual data into numerical features using **CountVectorizer**.
- Perform Exploratory Data Analysis (EDA).
- Train a Machine Learning model for spam classification.
- Evaluate model performance using multiple evaluation metrics.
- Build a reliable model capable of predicting unseen emails.
- Discuss practical deployment possibilities for real-world email filtering systems.

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- Scikit-learn
- Jupyter Notebook

---

##  Dataset

The project uses the **SMS Spam Collection Dataset (`spam.csv`)**, which contains labeled messages classified as:

- **Ham** – Legitimate messages
- **Spam** – Unwanted or fraudulent messages

---

##  Project Workflow

1. Import required libraries
2. Load the dataset
3. Data preprocessing
4. Exploratory Data Analysis (EDA)
5. Text cleaning and feature extraction
6. Train-test split
7. Train the Multinomial Naive Bayes model
8. Evaluate model performance
9. Predict whether a new message is Spam or Ham

---

##  Machine Learning Model

The project uses the **Multinomial Naive Bayes** algorithm because it performs exceptionally well on text classification tasks such as spam detection.

---

##  Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score
- Classification Report

---

##  Results

The trained model achieved excellent performance in detecting spam emails.

- **Accuracy:** ~98%
- High Precision
- High Recall
- Strong F1-Score

The model successfully classifies most spam messages while minimizing false positives.

---

##  Key Insights

- Approximately **13%** of the dataset consists of spam messages, while **87%** are legitimate (ham) messages.
- Frequently occurring spam keywords include:
  - **Free**
  - **Call**
  - **Win**
  - **Prize**
  - **Now**
  - **Text**
- The Multinomial Naive Bayes classifier proved highly effective for text classification due to its simplicity, speed, and strong predictive performance.

---

##  Practical Applications

This project can be integrated into:

- Email filtering systems
- Corporate email security
- Customer support platforms
- Messaging applications
- Anti-phishing systems

---

##  Ethical Considerations

This project focuses solely on message classification while respecting user privacy. Personal information and email identities should always be handled securely and responsibly when deploying such systems.

---

##  Future Enhancements

- Use TF-IDF Vectorization
- Compare multiple algorithms such as:
  - Support Vector Machine (SVM)
  - Random Forest
  - Logistic Regression
  - XGBoost
- Deploy the model using Streamlit or Flask
- Build a web interface for real-time spam prediction
- Improve detection of evolving phishing and spam techniques

---

##  Conclusion

This project demonstrates how Machine Learning can effectively solve real-world cybersecurity problems.

By preprocessing email data, extracting meaningful textual features, and training a **Multinomial Naive Bayes** classifier, we successfully developed a spam detection system capable of accurately distinguishing between spam and legitimate messages.

The model achieved an accuracy of approximately **98%**, making it suitable for practical spam filtering applications. This project highlights the importance of feature engineering, proper model evaluation, and data preprocessing in building reliable text classification systems.

Overall, the project provides a strong foundation for developing intelligent email filtering solutions and can be further enhanced with advanced Natural Language Processing (NLP) techniques and modern deep learning models.

---

##  Repository Structure

```
Spam-Email-Detection/
│── Email_Spam_or_Ham_Detection.ipynb
│── spam.csv
│── README.md
```

---

##  Author

**Gayathri**

Python | Machine Learning | Data Analytics | Data Science
