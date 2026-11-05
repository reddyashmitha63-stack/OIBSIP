# Sentiment Analysis of Amazon Fine Food Reviews

## About the Project

As part of my Oasis Infobyte Data Analytics Internship, I worked on this Sentiment Analysis project using the Amazon Fine Food Reviews dataset.

The main aim of this project was to analyse customer reviews and classify them into three categories: Positive, Negative, and Neutral. I wanted to understand how machine learning can be used to identify customer opinions from written reviews.

## Dataset

For this project, I used the Amazon Fine Food Reviews dataset.

I created sentiment labels based on the star ratings given by customers:

- 1–2 stars: Negative
- 3 stars: Neutral
- 4–5 stars: Positive

## Tools and Libraries Used

- Python
- Pandas and NumPy
- NLTK
- Scikit-learn
- Matplotlib and Seaborn
- WordCloud
- Google Colab

## Steps I Followed

1. Loaded the dataset and explored its contents.
2. Checked the distribution of customer ratings.
3. Created sentiment labels based on star ratings.
4. Cleaned the review text by converting it to lowercase, removing punctuation and stopwords, and applying lemmatization.
5. Used TF-IDF to convert the text into numerical features.
6. Split the dataset into training and testing sets in an 80:20 ratio.
7. Trained two machine learning models: Naive Bayes and Logistic Regression.
8. Evaluated both models using accuracy, precision, recall, F1-score, and confusion matrices.
9. Created WordClouds to display frequently used words in each sentiment category.
10. Examined five reviews that were incorrectly classified by the model.

## Model Results

After training and testing both models, I got the following results:

| Model | Accuracy | Weighted F1-score |
| Naive Bayes | 77.97% | 0.6956 |
| Logistic Regression | 84.18% | 0.8132 |

Logistic Regression performed better than Naive Bayes based on both accuracy and weighted F1-score.

## What I Learned

While working on this project, I got practical experience with text preprocessing, TF-IDF vectorization, and machine learning classification. I also learned how to evaluate different models and understand where they make incorrect predictions.

This project helped me understand how sentiment analysis can be useful for businesses to study customer feedback, identify common opinions, and improve their products and services.

## Limitation

One limitation of this project is that sentiment labels were created using star ratings. Sometimes the written review may express a different opinion from the rating given by the customer, which can affect the model's predictions.
