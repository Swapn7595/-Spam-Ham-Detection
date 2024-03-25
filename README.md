
# Spam Ham Detection Project
This project focuses on detecting spam and ham (non-spam) messages using Natural Language Processing (NLP) techniques. The goal is to classify messages as either spam or ham based on their content.

## Project Overview
The project involves the following key steps:
1. **Data Cleaning**: Cleaning the dataset by removing unwanted columns and duplicate records.
2. **Exploratory Data Analysis (EDA)**: Analyzing the distribution of spam and ham messages.
3. **Text Preprocessing**: Preprocessing text data by lowercasing, removing HTML tags, URLs, punctuation, stop words, and numbers, and lemmatizing the text.
4. **Feature Engineering**: Extracting features such as the number of characters, words, and sentences in the text.
5. **Text Vectorization**: Vectorizing text data using the Bag of Words approach.
6. **Model Building**: Building and evaluating various machine learning models including Naive Bayes, Logistic Regression, Random Forest, and more.
7. **Model Evaluation**: Evaluating model performance based on accuracy and precision scores.
8. **Extra Trees Classifier**: Highlighting the Extra Trees Classifier model that achieved 97% accuracy.


## Files Included
- `NLP_Spam_Ham_Detection_Project.ipynb`: Jupyter notebook containing the project code.
- `tfidf.pkl`: Pickle file containing the TF-IDF vectorizer.
- `ExtraTreesClassifier.pkl`: Pickle file containing the trained Extra Trees Classifier model.


## Getting Started
To run the project locally, follow these steps:
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook `NLP_Spam_Ham_Detection_Project.ipynb`.


## Usage
- Use the provided models to classify new messages as spam or ham.
- Experiment with different text preprocessing techniques and models for better performance.


## Contributors
- Swapnil R
