# Spam Email Classifier 🚨

A machine learning project to classify SMS messages as **Spam** or **Ham (Not Spam)** using NLP and classical ML algorithms.

## Dataset
- SMS Spam Collection Dataset from Kaggle
- 5,572 labeled messages (86.6% Ham, 13.4% Spam)

## Tech Stack
- Python, scikit-learn, NLTK, pandas, matplotlib
- TF-IDF Vectorization (unigrams + bigrams)
- Models: Naive Bayes, Logistic Regression, Linear SVM, Random Forest

## Best Model
**Linear SVM** — ~98.9% Accuracy | F1-Score: 0.973

## Project Structure
- `spam_classifier.ipynb` — Full notebook (EDA, preprocessing, training, evaluation)
- `spam_classifier_model.pkl` — Saved trained model
- `tfidf_vectorizer.pkl` — Saved TF-IDF vectorizer

## Results
| Model | Accuracy | F1-Score |
|---|---|---|
| Naive Bayes | ~97.2% | ~94.6% |
| Logistic Regression | ~98.7% | ~97.0% |
| Linear SVM | ~98.9% | ~97.3% |
| Random Forest | ~97.8% | ~95.0% |
