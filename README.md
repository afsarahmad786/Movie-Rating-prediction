
## Table of Contents (Optional)

- [Data collection](#Data_collection)
- [Understanding the data](#Understanding_data)
- [Data Cleaning](#Data_Cleaning)
- [Model Architecture](#Model_Architecture)

---


## Installation
### from conda
- `conda install -c anaconda tensorflow-gpu` 
### from pip
- `pip install tensorflow-gpu` 

## Data_collection
- the dataset is also provided
---

## Understanding_data
- data sets consist revies of movies 
- and it describes wheather it positive or negative

## Data_Cleaning
- first we convert it to lowercase
- remove all the punctuation etc
- we are using countvectorizer skip gram model to preprocess

### Model_Architecture
### we are using three diffrent classifier
- MultinomialNB
- BernoulliNB
- GaussianNB