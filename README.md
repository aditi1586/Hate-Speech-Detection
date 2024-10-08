# Hate-speech-Detection
![Static Badge](https://img.shields.io/badge/Python-3.8-blue)
![Static Badge](https://img.shields.io/badge/Framwork-Flask-red)
![Static Badge](https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-Purple)
![Static Badge](https://img.shields.io/badge/API-TMBD-yellow)
<br>
Hate speech has become a growing concern in today’s online world. Identifying and combating hate speech is important to maintain healthy and respectful discussions on various platforms. This Hate Speech Detection project is designed to help identify and classify text as hate speech or non-hate speech using machine learning algorithms.

The project consists of a Flask backend with a web frontend to make the model accessible and user-friendly.
# Features
1. **Text Classification**: Detects whether the input text contains hate speech or not.
2. **Machine Learning Model**: Trained on labeled data for hate speech detection.
3. **Web Interface**: A simple and interactive UI for users to test the model.
4. **Data Visualization**: Graphical representation of predictions and results.
5. **Responsive Design**: Mobile-friendly interface.
6. **Light-weight and Efficient**: Fast processing of text with minimal delay.

### Tech Stack
- **Frontend**:
  - HTML
  - CSS
  - JavaScript

- **Backend**:
  - Flask (Python)

- **Machine Learning**:
  - Scikit-learn (Python)
  - Natural Language Processing (NLP)
  - Pandas, Numpy

- **Deployment**:
  - Flask server for backend
  - Streamlit for quick deployment (optional)

# Architecture
![Screenshot (32)](https://github.com/user-attachments/assets/3d9332ad-1a91-4150-8ac6-d797332562f7)

# Model Training
The machine learning model used in this project is based on natural language processing (NLP) techniques. The following steps were used to train the model:

1. **Data Preprocessing**: Cleaning and preparing the dataset.
    -Tokenization
    -Removal of stop words
    -Lemmatization and stemming
2. **Vectorization**: Using CountVectorizer and TF-IDF to convert text to numerical format.
3. **Model**: Various classification models such as Logistic Regression, Naive Bayes, and Support Vector Machine (SVM) were evaluated.
4. **Evaluation**: The best-performing model was selected based on accuracy, precision, recall, and F1-score.

# Code for Model Training:
You can find the model training script in the **train_and_save_model.py** file. 
<br>
It handles data preprocessing, training, and saving the trained model.

# Source of the Dataset
1. [Twitter Hate Speech Dataset](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset)

# Dataset Features:
1. **id**: Unique identifier for the text.
2. **text**: The actual text data.
3. **label**: 0 for non-hate speech, 1 for hate speech.


