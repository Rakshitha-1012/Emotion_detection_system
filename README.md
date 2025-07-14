📘 Emotion Detection System (Text-Based)
🚀 Overview
This project is a machine learning–based system that detects emotions (joy, sadness, anger, fear, love, surprise) from text input using natural language processing (NLP) techniques.

🔍 Features
TF-IDF vectorization of input text
Logistic Regression classifier
Evaluation metrics: Accuracy, Precision, Recall, F1-Score
Visuals: Confusion Matrix, Metric Charts
Real-time emotion prediction from custom input

📂 Dataset
The dataset is split into train.txt, val.txt, and test.txt, with each line formatted as:
php-template
<sentence>;<emotion>

🧠 Model Accuracy
Overall Accuracy: 86%
Best performing classes: joy, sadness
Visual insights with confusion matrix & bar charts

💻 Requirements
pip install pandas scikit-learn nltk matplotlib seaborn
import nltk
nltk.download('punkt')  # if using NLTK tokenizer

🧪 Sample Use
predict_emotion("I am feeling so happy today!")  # Output: joy
