Aim of the Project

The aim of this project is to develop an intelligent machine learning model that can 
automatically classify text messages as spam (unwanted messages) or ham (legitimate messages).
By using Natural Language Processing (NLP) techniques and supervised learning algorithms, 
the system seeks to accurately detect and filter out spam messages, thereby improving communication efficiency,
reducing risks from fraudulent content, and enhancing user experience.


Project Description

Spam messages, commonly known as unwanted or fraudulent texts, are a growing issue in digital communication.
They not only create inconvenience for users but may also lead to privacy breaches, phishing attacks, 
and financial fraud. To address this problem, this project focuses on building an SMS Spam Detection 
System using Machine Learning and Natural Language Processing (NLP) techniques.

The dataset used in this project consists of 5,574 SMS messages, labeled as either ham (legitimate) 
or spam (unwanted). The raw text data is first preprocessed and converted into numerical features
using the Bag of Words (CountVectorizer) method. A Naïve Bayes Classifier, which is widely used 
in text classification tasks, is then trained on these features to distinguish between spam and ham messages.

The model is evaluated using metrics such as accuracy, precision, recall, and F1-score
to ensure reliable performance. Visualization techniques like confusion matrix heatmaps 
and bar charts are also employed to represent predictions graphically.

This system demonstrates how machine learning can be applied to build real-world applications
that automatically filter spam, saving users from fraudulent and unnecessary messages. 
The project can also be extended using TF-IDF, deep learning models, or transformer-based NLP techniques to achieve even higher accuracy.
