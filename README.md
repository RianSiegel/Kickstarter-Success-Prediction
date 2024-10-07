# Kickstarter Success Prediction

Kickstarter is a popular crowdfunding platform that has helped thousands of entrepreneurs and creators bring their innovative ideas to life. However, not all Kickstarter projects are successful, and understanding the factors that contribute to success or failure can be valuable for both creators and investors alike.

This project's aim was to gain insights into the characteristics of successful and unsuccessful Kickstarter projects (such as funding targets, project categories etc.) and - based on this information - develop a machine learning algorithm which is able to predict the outcome of future Kickstarter campaigns (i.e. success or failure) with the highest possible accuracy.

It was very clear from the beginning of the project that the scope of available data in the dataset is limited and even the best possible ML model could only do so much being based on only a small selection of mostly categorical variables.

The initial idea of predicting the amount raised with a regression model was tested with linear regression and KNN algorithms, but - due to poor results - was dropped in favor of binary classification. However, the files with the attempts at a regression model to predict the amount pledged are still included.

Binary classification was tested with logistic regression and KMeans models before landing on a Gradient Boosting Classifier for the final model which reached an accuracy of 70% (that can be considered quite good given the limited scope of the data).

Future improvements of the project could include analyzing and incorporating campaign description texts with NLP and image classification of the campaign's pictures using image recognition techniques.

Presentation slides for a fictitious pitch to possible investors in the project are also included in this repo.