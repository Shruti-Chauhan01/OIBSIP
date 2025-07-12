# 📧 Task 04: Email Spam Detection using Naive Bayes Classifier

This project is part of my Data Science internship at **Oasis Infobyte**, focused on building a machine learning model to classify emails as **spam** or **not spam (ham)** using the Naive Bayes algorithm.

---

## 📌 Objective

To accurately detect spam emails by training a **Multinomial Naive Bayes** classifier on a labeled dataset of email messages, utilizing text feature extraction techniques.

---

## 🔍 Problem Statement

Email spam detection is crucial for improving user experience and security by filtering unwanted messages. This project develops a text classification model to automatically identify spam emails based on their content, helping reduce phishing, scams, and unsolicited marketing.

---

## 🛠️ Tools & Technologies Used

- **Python**  
- **Jupyter Notebook**  
- **Pandas** – data handling  
- **Scikit-learn** – feature extraction, model building, evaluation  
- **CountVectorizer** – converting text into numeric feature vectors  
- **Multinomial Naive Bayes** – probabilistic classifier suited for discrete features like word counts  

---

## 📊 Methodology

1. **Data Loading & Preprocessing**  
   - Loaded `spam.csv` dataset containing email texts and labels  
   - Cleaned data by selecting relevant columns (`label` and `message`)  
   - Encoded labels: `ham` → 0 (not spam), `spam` → 1 (spam)

2. **Train-Test Split**  
   - Split dataset into 80% training and 20% testing sets to evaluate model generalization

3. **Feature Extraction**  
   - Used `CountVectorizer` to convert text messages into a matrix of token counts suitable for model input

4. **Model Training**  
   - Trained a **Multinomial Naive Bayes** classifier on the training data

5. **Model Evaluation**  
   - Predicted labels on the test set  
   - Evaluated performance using:
     - **Accuracy Score**  
     - **Confusion Matrix**  
     - **Classification Report** (precision, recall, f1-score)

6. **Sample Prediction**  
   - Tested the model on a custom example email to demonstrate prediction capability

---

## 📈 Results

- **Accuracy:** ~98.39%  
- **Confusion Matrix:**  '''[[963 2]
                             [ 16 134]]'''
- **Classification Report:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| Ham (0) | 0.98      | 1.00   | 0.99     | 965     |
| Spam (1) | 0.99      | 0.89   | 0.94     | 150     |

- The model shows excellent performance, especially in identifying non-spam emails with high recall and precision. Slightly lower recall for spam indicates some spam emails are missed but still overall very effective.

---

## 🖼️ Sample Output

Sample email: "Congratulations! You've won a prize. Click to claim."
Prediction: Spam


---

## 🔗 Important Links

- 🌐 [Oasis Infobyte Website](https://www.oasisinfobyte.com/)  
- 📁 [GitHub Repository](https://github.com/Shruti-Chauhan01/OIBSIP/tree/main/OIBSIP_DS_04)  
- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/shruti-chauhan-35b082338/)  
- 📧 [Email Me](mailto:shrutihcauhan0086@gmail.com)  

---

## 💡 Key Learnings

- Effective text preprocessing and feature extraction using `CountVectorizer`  
- Applying Multinomial Naive Bayes for text classification problems  
- Interpreting classification metrics (accuracy, precision, recall, f1-score)  
- Practical implementation of spam filtering using machine learning techniques  

---

> *“Machine learning empowers us to build smart systems that filter noise and deliver value.”*

---

**© 2025 | Shruti Chauhan**  
🔗 [GitHub](https://github.com/Shruti-Chauhan01) • [LinkedIn](https://www.linkedin.com/in/shruti-chauhan-35b082338/)
