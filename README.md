# Information Retrieval Project: Anime Genres Multilabel Classification
Information retrieval project which our team try to make anime genres multi label classification through the synopsis. 

## DATASET
https://www.kaggle.com/aludosan/myanimelist-anime-dataset-as-20190204

## Data Preprocessing
For data preprocessing for the synopsis cleaning up the data by removibng the punctuation, number, null and after that give it stopword to remove the a of the and etc and lastly giving it stemming from nltk. As for the target we simply giving it one hot encoder by making into a list of binary.
## Word vectorize
word vectorized are devided into two group which is tf-idf and bert encoder as bert have its own encoding.
## Model
for the the model that we are using are linear regression which come in a result of 33%.
as for bert with a small modification adding BertModel(pretrain) - dropout - linear to do the multi-label classification and got 40% for the score

## Conclusion
To give an improvement we can group the genres which are identical into one to make the dataset even simpler
