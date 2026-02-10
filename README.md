Sport vs Politics Text Classifier

This project implements a binary text classification system to classify text documents into Sport or Politics categories.
Multiple traditional machine learning pipelines are trained and their performances are compared.

📌 Project Overview

The objective of this project is to:

Read raw text data from a file

Train multiple ML-based text classifiers

Predict whether a given text belongs to Sport or Politics

Compare the results of different models

📂 Dataset

Input data is stored in a file named data.txt

Each line contains a text sample with an associated label

Labels:

0 - sport

1 - politics

🧠 Models Used

Three different pipelines are implemented:

1. TF-IDF + Support Vector Machine (SVM)

TF-IDF for feature extraction

Linear SVM for classification

Performs well on high-dimensional sparse text data

2. TF-IDF + Logistic Regression

TF-IDF vectorisation

Logistic Regression classifier

Faster training and good baseline performance

3. Bag of Words (BoW) + Multinomial Naive Bayes (MLB)

Count-based BoW features

Multinomial Naive Bayes classifier

Simple and efficient probabilistic model

🔄 Workflow

1. Load text data from data.txt

2. Preprocess text (tokenisation, cleaning)

3. Convert text into numerical features

4. Train all three models

5. Predict class labels (Sport / Politics)

6. Evaluate and compare model performance

📊 Evaluation

Models are compared using standard classification metrics such as:

1.Accuracy

2.Precision

3.Recall

4.F1-score

The final comparison highlights the strengths and weaknesses of each pipeline.

🛠️ Technologies Used

Google Colab Enviroment

Python

scikit-learn

NumPy

Pandas
