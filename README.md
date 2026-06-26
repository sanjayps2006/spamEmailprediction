# 📧 𝐒𝐩𝐚𝐦 𝐄𝐦𝐚𝐢𝐥 𝐃𝐞𝐭𝐞𝐜𝐭𝐢𝐨𝐧 𝐔𝐬𝐢𝐧𝐠 𝐋𝐨𝐠𝐢𝐬𝐭𝐢𝐜 𝐑𝐞𝐠𝐫𝐞𝐬𝐬𝐢𝐨𝐧

> 🤖 **A Machine Learning Project to Classify Emails as Spam or Not Spam Using Natural Language Processing (NLP)**

---

## ✨ 𝐀𝐛𝐨𝐮𝐭 𝐓𝐡𝐞 𝐏𝐫𝐨𝐣𝐞𝐜𝐭

This project uses **Logistic Regression** and **TF-IDF (Term Frequency-Inverse Document Frequency)** to classify email messages as **Spam** or **Not Spam**.

The model is trained using sample email messages and predicts whether a newly entered email is spam based on its text content.

---

## 🎯 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞𝐬

✔ Convert email text into numerical features using TF-IDF

✔ Train a Logistic Regression classifier

✔ Predict whether an email is Spam or Not Spam

✔ Demonstrate a simple Natural Language Processing (NLP) application

---

## 📂 𝐃𝐚𝐭𝐚𝐬𝐞𝐭

### Sample Training Emails

| Email Message | Label |
|--------------|-------|
| Congratulations! You have won a free iPhone | Spam |
| Claim your prize now | Spam |
| Limited time offer, click here | Spam |
| Meeting scheduled for tomorrow | Not Spam |
| Please submit the assignment | Not Spam |
| Let's have lunch together | Not Spam |

### Target Labels

- **1 → Spam**
- **0 → Not Spam**

---

## 🛠️ 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐢𝐞𝐬 𝐔𝐬𝐞𝐝

- 🐍 Python
- 🤖 Scikit-learn
- 📝 TF-IDF Vectorizer
- 📊 Logistic Regression

---

## 📦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐝 𝐋𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬

Install the required library:

```bash
pip install scikit-learn
```

---

## ▶️ 𝐇𝐨𝐰 𝐓𝐨 𝐑𝐮𝐧

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/spam-email-detection.git
```

### 2️⃣ Navigate to the project folder

```bash
cd spam-email-detection
```

### 3️⃣ Run the program

```bash
python spam_email_detection.py
```

## 📸 𝐒𝐚𝐦𝐩𝐥𝐞 𝐎𝐮𝐭𝐩𝐮𝐭

### Example 1

```text
Enter the email message:
Congratulations! Claim your free reward now.

Spam Email
```

### Example 2

```text
Enter the email message:
Please attend the meeting at 10 AM tomorrow.

Not Spam Email
```

---

## ⚙️ 𝐇𝐨𝐰 𝐈𝐭 𝐖𝐨𝐫𝐤𝐬

1. Import the required libraries.
2. Create a sample email dataset.
3. Convert email text into numerical features using TF-IDF.
4. Train the Logistic Regression model.
5. Accept a new email message from the user.
6. Predict whether the email is Spam or Not Spam.
7. Display the prediction.

---

## 📚 𝐌𝐚𝐜𝐡𝐢𝐧𝐞 𝐋𝐞𝐚𝐫𝐧𝐢𝐧𝐠 𝐀𝐥𝐠𝐨𝐫𝐢𝐭𝐡𝐦

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for binary classification problems. It predicts the probability of an input belonging to one of two classes.

### TF-IDF Vectorizer

TF-IDF converts text into numerical feature vectors by measuring the importance of each word in a document relative to all documents.

**Advantages:**

- ✔ Fast and efficient
- ✔ Works well for text classification
- ✔ Simple to implement
- ✔ Suitable for spam detection

---

## 🚀 𝐅𝐮𝐭𝐮𝐫𝐞 𝐄𝐧𝐡𝐚𝐧𝐜𝐞𝐦𝐞𝐧𝐭𝐬

⭐ Train the model using a larger real-world email dataset

⭐ Improve accuracy using advanced NLP techniques

⭐ Add email preprocessing (stop-word removal, stemming, lemmatization)

⭐ Build a web application using Streamlit or Flask

⭐ Deploy the model for real-time spam detection

---

## 📁 𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐒𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞

```
Spam-Email-Detection/
│
├── spam_email_detection.py
├── README.md
└── requirements.txt
```

---

## 👨‍💻 𝐀𝐮𝐭𝐡𝐨𝐫

**Sanjay palaniyappan senthil kumar**

---

## 📄 𝐋𝐢𝐜𝐞𝐧𝐬𝐞

This project is licensed under the **MIT License**.

---

⭐ **If you found this project useful, please consider giving it a ⭐ Star on GitHub!**
