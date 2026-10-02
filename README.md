# 📩 SMS Spam Detection using NLP

A machine learning project that classifies SMS messages as Spam or Ham (Not Spam)
using Natural Language Processing and machine learning techniques.  

---

## 🚀 Project Overview

1. Data Preprocessing
- Loaded and cleaned the SMS dataset.
- Removed unnecessary characters and processed the text.
- Tokenized the messages and prepared them for feature extraction.

2. Feature Extraction
- Used TF-IDF to convert text messages into numerical features.

3. Model Training
- Trained a Naive Bayes classifier to classify messages as Spam or Ham.

4. Model Evaluation
- Evaluated the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF
- Naive Bayes
- Matplotlib
- Seaborn 

---

## 📊 Results

- Accuracy: 95.25%
- Spam Precision: 68%
- Spam Recall: 100%
- Spam F1-Score: 81%
- Weighted F1-Score: 96%

The model was evaluated using accuracy, precision, recall, F1-score, and a confusion matrix. 

---

## 📂 Project Structure

```
SMS-Spam-Detection/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── yelp.csv
└── smsspamcollection/
```

---

## ⚙️ How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/HemanthN17/SMS-Spam-Detection.git
   cd SMS-Spam-Detection
   ```

2. **Create a virtual environment (recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Download NLTK resources**  
   In a Python shell or notebook, run:  
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   ```

5. **Run the Notebook**  
   ```bash
   jupyter notebook notebook.ipynb
   ```

---

## 🎯 Future Work

1. Experiment with additional machine learning classification algorithms.
2. Improve text preprocessing and feature extraction.
3. Build a web interface for real-time SMS spam prediction.
4. Explore advanced NLP techniques and deep learning models.  

---

## 👨‍🎓 About Me  

I’m Hemanth Nirigitti, a Computer Science and Engineering graduate specializing in Artificial Intelligence and Machine Learning.

I am interested in Python, Machine Learning, Natural Language Processing, Artificial Intelligence, and Web Development.

This project helped me gain practical experience in NLP, text preprocessing, feature extraction, machine learning classification, and model evaluation. 
