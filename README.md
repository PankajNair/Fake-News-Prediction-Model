# Fake News Prediction Model
## Problem Statement
In recent years, fake news has become a significant issue globally, with the potential to cause significant harm to individuals and society. With the rise of social media and digital communication channels, it has become easier for fake news to spread rapidly, leading to misinformation and confusion among the public. As a result, there is an urgent need for a reliable system that can accurately identify and predict the occurrence of fake news. The success of this model would have significant implications for journalism, politics, and society as a whole, helping to promote accurate information and prevent the spread of misinformation.
## Data Information
The dataset can be download using this [link](https://www.kaggle.com/c/fake-news/data?select=train.csv).

The dataset contains a unique id for a news article, the title of a news article, author of the news article, the text of the article (could be incomplete) and a label that marks the article as potentially unreliable. 1 indicates an unreliable article and 0 indicates a reliable article.
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. As the current dataset is textual, we create a custom stemming functions using functions from the sklearn and nltk libraries and vectorize the outputs to numerical data.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use the Decision Tree Classifier as our model available in the sklearn library. We also need to evaluate the models using appropriate evaluation metrics.
