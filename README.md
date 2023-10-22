# Fake-news-prediction

This project is aimed at developing and evaluating machine learning models for the detection of fake news articles. 
We utilized a diverse dataset to train three popular classification algorithms: 
1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **k-Nearest Neighbors (KNN).** 

These models are designed to distinguish between legitimate news articles and deceptive or misleading content. 
We conducted extensive text preprocessing, including TF-IDF vectorization, to transform textual data into numerical features.Additionally as part of our text preprocessing pipeline, we employed stemming to reduce words to their root forms, aiding in the simplification and analysis of text data. Since the news text is very large so all the computation is conducted on combination of news title and author name. The project is well commented for easy understanding. 


Our analysis also includes a **comparative performance assessment** of these algorithms to determine which one excels in fake news prediction.

Whether you're interested in understanding the intricacies of fake news detection or seeking a benchmark for your own text classification tasks, this project provides valuable insights into the world of misinformation identification.


**About the Data Set:**
1. **id:** unique id for a news article
2. **title:** the title of a news article
3. **author:** author of the news article
4. **text:** the text of the article; could be incomplete
5. **label:** a label that marks whether the news article is real or fake:
   1. 1: Fake news
   2. 0: real News
