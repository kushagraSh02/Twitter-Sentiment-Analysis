# Twitter-Sentiment-Analysis
Performing sentiment analysis on twitter dataset.

Here, we perform sentiment analysis on twitter data. first we perform preprocessing by removing stopwords and puntuations from the data and then we pass it to a simple model to predict the sentiment. The model consists of an Embedding layer, a bidirectional layer, an attention layer and an output dense layer. we use Adam optimizer to optimize model loss.

**Dataset Overview**
This is an entity-level sentiment analysis dataset of twitter. Given a message and an entity, the task is to judge the sentiment of the message about the entity. There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral.

### Dataset Url:
https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis
 
### **Dependencies**
```
1. nltk
2. spacy
3. numpy
4. pandas
5. keras
6. Tensorflow
7. matplotlib
8. sklearn
9. wordcloud
```
