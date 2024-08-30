# NLP - Emotion-Classification-in-Text

This project that aims to classify emotions from text data

Dataset The program uses a dataset called "nlp_dataset.csv" which contains text comments and their corresponding emotions (anger, fear, or joy).

Preprocessing

The program loads the dataset and displays the first few rows. It performs text cleaning by converting all text to lowercase, removing digits, and removing non-word characters. It tokenizes the text into individual words or tokens. It removes stopwords (common words like "and", "the", etc. that don't carry much meaning). Feature Extraction:

The program uses the CountVectorizer from scikit-learn to convert the text data into a matrix of token counts. It fits and transforms the data using the CountVectorizer.

Model Development:

The program splits the data into training and testing sets (80% for training and 20% for testing). It trains two machine learning models: Naive Bayes and Support Vector Machine (SVM). It evaluates the performance of both models using metrics like accuracy, precision, recall, and F1-score. Model Comparison:

The program compares the performance of both models and determines that the SVM model is the best model for emotion classification based on its higher accuracy, precision, recall, and F1-score. Conclusion:

The program demonstrates the use of NLP techniques and machine learning models to classify emotions from text data. The SVM model is found to be the best model for this task.
