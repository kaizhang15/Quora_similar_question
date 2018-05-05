# Quora_similar_question

This project is prepared for course machine learning. 

We mainly use NLP and Keras CNN to implement the app which can be used to tell whether two input questions have the same meaning.

The dataset is downloaded from Kaggle and we don't change it. 

There are some files in the folder:

* Questions with same meaning?.ipynb: is the notebook file which we use to implement and test.
* Input folder: contain train.csv, test.csv, vectors.txt
* GloVe folder: glove is developed by Stanford and is used to do NLP. We call glove to process the txt data we get from dataset. There is a Readme file which will explain how to use it. (Maybe the version of glove is Mac, you can download PC version by yourself.)

### Usage

To use it, first go to the folder of project and input `jupyter notebook` in Terminal/Cmd to open the environment, and run `Questions with same meaning?.ipynb` file.

Then you can change input training set and testing set name to use your own data. And if you change the training set, you need to output txt file as the last cell in this notebook. Then train this data to vectors with glove.

The app will output a `test_predictions.csv` file as result.