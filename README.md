# Linguistics Hate Speech Classification Project

## Project Overview
This data science project leverages machine learning to classify text as hate speech or not and to determine the intensity of the hate speech according to the "hate speech intensity scale". The project utilizes two approaches: lexicon-based and supervised machine learning models.

The first approach uses lexicons and dictionaries to classify text from Quora as hate speech or not. The second approach employs supervised machine learning models such as Naive Bayes, Random Forest, and SVM to classify the text and determine the intensity of the hate speech.

## Data Visualization
For data visualization, bar and pie charts were used to check the distribution of the dataset and a word cloud to identify commonly used words in hate speech and non-hate speech.

## Data Pre-processing
**Duplicate Removal:** Ensures there are no repeated entries in the dataset.
**Lemmatization:** Reduces words to their base or root form.
**Stop Words Removal:** Eliminates common words that do not contribute to the meaning of the text.
**Vectorization and Feature Extraction:** Uses TF-IDF and n-grams to convert text into numerical features.

## Model Building
**Data Splitting:** The dataset is split into 80% training and 20% testing sets.
**Model Training:** Uses Scikit-learn to train models such as Naive Bayes, Random Forest, and SVM.

## Model Validation
Several metrics were used to validate the models:

**Precision:** Measures the accuracy of positive predictions.
**Recall:** Measures the ability to find all relevant instances.
**F1-score: **Harmonic mean of precision and recall, providing a balance between the two.
**Confusion Matrix:** Shows the performance of the classification model.
**K-Fold Cross-Validation:** K-fold cross-validation was employed to estimate the average accuracy of the models and prevent overfitting.
These metrics ensure that the models are evaluated comprehensively, highlighting their strengths and weaknesses.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code adheres to the project's coding standards and includes appropriate tests.

## Contact
For any questions or inquiries, please contact the project maintainers at josepaolonicolas@gmail.com.