in this dataset we have to predict sentiment on the basis of review 
we follow a proper pipeline in this project
firstly=we upload our dataset which i picked from kaggle 
second= we convert all text  into lower case
third= we remove all punctation from our text in review column
fourth=we remove all the number and emoji
fifth=now for removing stopwords like the ,is etc we have two method one is tokenisation and one is split method but in split method there was a limitation to use split methos we 
have to ensure that we remove all punctation from text
after this we train test our dataset now xtrain,xtest have to convert it into numerical then only ml can understand that
for that we use feature extraction method the two method we use here in this project are countvectoriser,tfidfvectoriser
the model we use here naive bayes multinomialnb model and logistics regression model 
the accuracy we get by countvectoriser feature extraction method and multinomialnb model is 85 percent
the accuracy we get by tfidfvectoriser feature extraction method and multinomialnb are 86 percent
the accuracy we get by tfidf vectoriser feature extraction method and logistics regression are 89 percent
