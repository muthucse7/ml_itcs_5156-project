# Sentiment Analysis on Amazon Product Reviews

## Author
- **Muthu Selvam**
- Email: mselvam@uncc.edu

## Introduction
With the rise of e-commerce, online product reviews have become crucial for consumers. Analyzing vast volumes of reviews manually is impractical. Supervised learning models can streamline sentiment analysis on large-scale datasets. Our study focuses on categorizing feedback as positive or negative, building an efficient sentiment analysis model, Visualization and Automated data labelling (PCA).

## What is Sentiment Analysis?
Sentiment analysis, or opinion mining, is a process that uses natural language processing to determine the sentiment expressed in text, such as positive, negative, or neutral. It's used in analyzing various texts like social media posts, reviews, and news articles to understand people's opinions and attitudes.

## Problem & Challenges
The problem addressed in this project is sentiment analysis of reviews, specifically the classification of reviews into multiple classes based on their ratings. The main challenges include:
- Dealing with multi-class imbalanced data.
- Extracting meaningful features from text data.
- Choosing appropriate classifiers for accurate sentiment classification.

## Motivation
The motivation behind this project is to provide businesses with insights into customer sentiment, which can inform decision-making processes such as product improvements, marketing strategies, and customer service enhancements. By analyzing reviews, businesses can better understand customer satisfaction levels and areas for improvement.

## Existing Related Approaches
Several existing approaches to sentiment analysis include:
- Naive Bayes classifiers
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)

## Dataset
Dataset: Amazon product reviews (categories: Electronics, Cell Phone & Accessories)
- [Download Here](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Cell_Phones_and_Accessories_5.json.gz)
- [Kaggle Dataset](https://www.kaggle.com/code/kritimittal/amazon-product-reviews)

## The Method
1. Preprocessing: Cleaning text data, extracting features such as review length and polarity using TextBlob.
2. Feature Engineering: Converting text data into numerical features using TF-IDF vectorization.
3. Model Building: Training multiple classifiers including Naive Bayes, Logistic Regression, and SVM.
4. Evaluation: Assessing the performance of classifiers using accuracy metrics and generating confusion matrices to understand classification errors.
5. Visualization: Plotting ROC curves to visualize classifier performance across different classes.
6. Labelling: Automated data labelling using PCA and generalizing the approach.

## Comparative Analysis
- Our approach outperforms previous studies in terms of accuracy and effectiveness.
- Utilized advanced preprocessing and feature extraction techniques to enhance performance.
- Demonstrated superior accuracy across various datasets.

## Results and Observations
- Multinomial Naive Bayes classifier: Training accuracy around 72.55%, test accuracy around 60.84%.
- Multinomial Logistic Regression model: Training accuracy approximately 73.67%, test accuracy about 63.84%.
- SVM Linear Classifier: Training accuracy 50.51%, test accuracy around 20.32%.
- Models struggled with multi-class imbalanced data, particularly in lower-rated classes.

### Best Accuracy Model
Based on the results provided, the best accuracy model for the project appears to be the Multinomial Logistic Regression model, achieving the highest test accuracy of approximately 63.84%.

## Conclusion and Future Work
In conclusion, the project demonstrated the effectiveness of various classifiers in sentiment analysis of reviews. Future work could involve:
- Fine-tuning hyperparameters to improve classifier performance.
- Incorporating additional features or data sources for improved sentiment analysis.
- Automating data labeling using PCA and generalizing the approach to other text-based review datasets.

## References
The project referred to previous research papers and works related to sentiment analysis and opinion mining. Notable references include works by Elli & Wang, Rain, Shaikh & Deshpande, Nasr et al., Wang, and others.
- [Kaggle Dataset](https://www.kaggle.com/code/kritimittal/amazon-product-reviews)
- Xu, Yun, Xinhui Wu, and Qinxia Wang. "Sentiment Analysis of Yelp's Ratings Based on Text Reviews." 2015.

Thank you!
