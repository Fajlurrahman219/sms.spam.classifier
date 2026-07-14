# 📩 SMS Spam Classifier

An end-to-end Machine Learning project that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP), TF-IDF Vectorization, and a Multinomial Naive Bayes classifier. The application is deployed using **Streamlit Cloud**.

---

## 🚀 Live Demo

👉 **Live App:** https://smsspamclassifier-ajhuwfvwpki7rnbheezyyt.streamlit.app/

---

## 📌 Features

- 📩 Detects whether an SMS is Spam or Not Spam
- 🔤 Text preprocessing using NLTK
- ✂️ Tokenization
- 🧹 Stopword Removal
- 🌱 Porter Stemming
- 📊 TF-IDF Vectorization
- 🤖 Multinomial Naive Bayes Classifier
- 🌐 Interactive Streamlit Web App
- ☁️ Deployed on Streamlit Cloud

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Streamlit
- Pickle
- Git & GitHub

---

## 📂 Project Structure

```
sms.spam.classifier/
│
├── app.py                 # Streamlit application
├── main.py                # Training script
├── spam.csv               # Dataset
├── model.pkl              # Trained ML model
├── vectorizer.pkl         # TF-IDF Vectorizer
├── requirements.txt       # Dependencies
├── Procfile
├── setup.sh
├── README.md
└── sms-spam-detection.ipynb
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Fajlurrahman219/sms.spam.classifier.git
```

Move into the project directory

```bash
cd sms.spam.classifier
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit app

```bash
streamlit run app.py
```

---

## 🧠 Machine Learning Pipeline

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Text Preprocessing
5. Tokenization
6. Stopword Removal
7. Stemming
8. TF-IDF Vectorization
9. Model Training
10. Model Evaluation
11. Streamlit Deployment

---

## 📊 Algorithm Used

**Multinomial Naive Bayes**

Why this algorithm?

- Fast training
- Excellent for text classification
- Works well with TF-IDF features
- High accuracy for spam detection

---

## 📈 Dataset

Dataset contains SMS messages labeled as:

- **Ham (Not Spam)**
- **Spam**

---

## 📷 Application Preview

### Home Page

*(Add a screenshot here after uploading it to GitHub)*

---

## 🧪 Example

**Input**

```
Congratulations! You have won a FREE iPhone.
Click here to claim your prize.
```

**Prediction**

```
🚨 Spam Message
```

---

**Input**

```
Hey, are you coming to college today?
```

**Prediction**

```
✅ Not Spam
```

---

## 📦 Requirements

```
streamlit
pandas
numpy
scikit-learn
nltk
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 👨‍💻 Author

**Fajlur Rahman**

📧 Email: fajlurrahman219@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/fajlurrahman219/

🐙 GitHub: https://github.com/Fajlurrahman219

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub.
