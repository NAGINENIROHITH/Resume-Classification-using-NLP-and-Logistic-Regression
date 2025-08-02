# 🧾 Resume Classification using NLP and Machine Learning
This project focuses on classifying resumes into different job categories using Natural Language Processing (NLP) techniques and a simple Logistic Regression classifier.

# 📌 Objective
To preprocess raw resume text, extract meaningful features using TF-IDF, and build a classification model to predict the resume’s job category accurately.

# 🧠 Key Features
Real-world resume dataset (~13,000+ samples)

Text preprocessing with spaCy:

Tokenization

Lowercasing

Stopword removal

Lemmatization

TF-IDF vectorization

Classification using Logistic Regression

Model evaluation using accuracy score and classification report

# 📂 Dataset
We use the Resume Classification Dataset from Kaggle, which includes resumes labeled by job category (e.g., Data Science, HR, Design, etc.).

# 🔧 Installation & Requirements
Install dependencies in Google Colab or your local environment:
```
pip install pandas scikit-learn spacy kaggle
python -m spacy download en_core_web_sm
```
# 🚀 How to Run
Upload your Kaggle API token (kaggle.json)

Download and extract the dataset

Run the full pipeline in Colab:

Preprocessing

TF-IDF vectorization

Model training and testing

View accuracy and classification metrics

# 📈 Results
Achieved an accuracy of ~85% using Logistic Regression on the cleaned and vectorized resume text. Classification report provides insights into precision, recall, and F1-score across job categories.
