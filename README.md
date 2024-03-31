Sentiment analysis,  also known as Opinion Mining or Emotion AI, is a  field that involves analyzing large volumes of text to determine the expressed sentiment.  It  systematically identifies, extracts, quantifies, and studies affective states and subjective information from text  so as to determine whether the text conveys a positive, negative, or neutral sentiment. In real life, organizations apply Sentiment Analysis to monitor what people are saying about their products, services, and brand online. By analyzing social media posts, reviews, and customer interactions, companies gain insights into customer sentiment. This is widely used by organizations since opinions expressed on social media can significantly impact a brand’s reputation.  Sentiment analysis extracts meaningful insights from vast amounts of unstructured data. It enables organizations to make informed decisions based on customer feedback. In summary, sentiment analysis empowers organizations to understand customer feelings, enhance experiences, and make data-driven decisions. 

In the current project, I’ve dealt with a case of an  Airline Company with the customer review datasets provided for Training, Development and Test. For the purpose of predicting the sentiments of the test dataset, steps followed include data cleaning, data preprocessing, applying  shallow and deep classifiers, using e ensembled approaches, applying  machine learning techniques and performing  data augmentation, whenever  necessary.

For shallow classifier, the Naïve Bayes classifier is applied,  Code 1 demonstrates the entire project with Naïve Bayes classifier.  While the accuracy of this model for the training dataset is calculated as 52.42%, the same for the test dataset was found to be  54.78%.

Subsequently, for Deep Learning, Simple Neural Network ( SNN) has been applied. Code 2 below  demonstrates the entire project with SNN. The accuracy level achieved in this case, for the training dataset is 51.51%

Data augmentation is hard to implement on text data . Smote was tried but  with limited success.

Other than SNN, Convolutional Neural Network (CNN) and  Long Short-Term Memory (LSTM)  models  have also been tried out in this project. 

