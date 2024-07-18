# Hate-Speech-Detection
A Hate speech detection model
What was the model all about? It was a machine learning model trained to classify text as either ‘Hate Speech’, ‘Offensive Speech’ or ‘No Hate No Offense’.
How was it built? It was built by feeding a dataset containing tweets from X into an algorithm (DecisionTreeClassifier) which trains the model. Of course the necessary preprocessing like; removal of mentions, punctuations and stopwords were done, tokenization and stemming (PorterStemmer from nltk.stem) were equally done before the splitting of the dataset into 33% test and 67% training data.
What was the result like? The should 0.873945470 accuracy and can mostly predict texts appropriately.
What libraries are required? Numpy, Pandas, sklearn, re, and nltk
