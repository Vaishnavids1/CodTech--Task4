Name: Vaishnavi Deoaro Sonkusare 
Company: CODTECH IT SOLUTIONS 
ID: CT08DG1674 
Domain: Python Programming 
Duration: June to August 2025 
Mentor: NEELA SANTOSH KUMAR

Project Title: SMS Spam Detection using Machine Learning

<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/38cfbdb5-8d59-46be-8b19-be2d1eb96b40" />


Objective:
To develop a machine learning model that can classify SMS messages as Spam or Ham (Not Spam) using text processing and classification techniques.

Workflow Overview:
Dataset Loading
Loads the SMS dataset from a .tsv file containing message text and labels (spam or ham).
Data Exploration
Displays sample data and checks the distribution of spam vs. ham messages.
Label Encoding
Converts labels into binary format:
ham → 0
spam → 1
Feature Extraction (TF-IDF)
Uses TfidfVectorizer to convert text messages into numerical vectors.
Removes stopwords for better accuracy.
Train-Test Split
Splits data into 80% training and 20% testing sets.
Model Training
Trains a Multinomial Naive Bayes classifier on the training data.
Prediction & Evaluation
Predicts spam/ham labels for test data.
Calculates accuracy, precision, recall, and F1-score.
Creates a confusion matrix to visualize performance.

Visualization
Uses a heatmap to display the confusion matrix for better interpretation.

Model Saving
Saves the trained model and TF-IDF vectorizer using joblib for future use.

Technologies Used:

Python
Pandas, NumPy (data handling)
Scikit-learn (ML model, vectorization, evaluation)
Seaborn & Matplotlib (visualization)
Joblib (model persistence)

Key Features:

Automated text preprocessing and feature extraction.
High accuracy spam detection.
Visual representation of results.
Model and vectorizer saved for deployment.
