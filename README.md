# Towards Author Verification ( Identifying authors of unknown Tweets)

Abstract
In this project, intelligent systems were developed that takes a piece of tweet and based on stylometric analysis identifies the author or the tweet or Twitter account holder. This classification is done using six standard supervised classifiers: Artificial Neural Network (ANN), Logistic Regression (LR), Support Vector Machine (SVM), Naïve Bayes (NB), Random Forest (RF), and Decision Trees (DT). A hybrid neural network  Convolutional-Neural-Network_Long-Short-term-Memory (CNN-LSTM) was also trained. Furthermore, an unsupervised K-means clustering method was employed to determine how well the various features cluster into various stylometric. 
Using standard classifiers, stylometric features were extracted and used to train the various classifiers using cross-validation. The trained models were then tested for performance comparison. For the CNN-LSTM, the tweets were fed directly into the model which extracted features. Converting them to numbers in a vector space, and finally classifying them.
Project Aim
This project aims to develop machine learning classification models to label unknown tweets by authors, or Twitter handles by identifying an author’s writing style and determining if the tweet is a fake if ascribed to a predicted author different from the actual author.
This second instalment of the project aims to design, develop, and test various machine-learning classification models that can be used for author identification of unlabelled tweets. These models will then be evaluated and compared to determine the best performing models.
Project Objectives
1)	To appraise the literature thoroughly and critically behind author attribution of textual documents and microblogs
2)	To scrape and analyse a suitably sized dataset of tweets and authors
3)	To train different classification models to attribute tweets to their authors
4)	To evaluate the models to perform classification tasks
5)	To suggest the most suitable model for this classification task
Summary of Investigation Report
Functional Requirements of the Project
These functional requirements encompass deliverables and tasks that the project must achieve. The essential parts of this project that must make it function include:
1.	There must be a dataset to train the model
2.	The classification model short be able to accept unlabelled short tweets as inputs
3.	Selected user accounts should undergo the training
4.	The model should be able to determine the author of the unlabelled short tweet
Non-Functional Requirements of the Project
The non-functional requirements of the projects include the following:
1.	The package must be run in python
2.	The language or profile of the tweet must be in English
3.	The classification model should be trained with a limited number of resources in time, computational power, and data volume
4.	The dataset should be scraped from Twitter
5.	The accuracy of the model on an unlabelled tweet should be reasonable
6.	The authors or users would have a certain threshold number of tweets
