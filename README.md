# EmotionModelTraining
# Highlights:


This is a multi-class text classification (sentence classification) problem.

The purpose of this project is to classify emotions from sentences into 7 different categories.

The model was built with Long short-term memory(LSTM),Convolutional Neural Network (CNN) and Word Embeddings on Tensorflow.


#Train:
To run CNN for classifcation: Cnn_glove.ipynb
                              
                              Cnn_W2V.ipynb

To run LSTM for classification: lstm_glove.ipynb
                                
                                lstm_glove_prétraitement.ipynb
                               
                                lstm_w2v.ipynb
    

## Install dependencies
To get a development environment running you should :

Install virtualenv  :

```

pip install virtualenv

```

Create a new virtual environment and easily install all libraries by running the following command :

```

conda create  --name venv_name  --file requirements.txt

```

In the file requirements.txt you find all necessary dependencies for this project.

To activate the new environment:

```

source activate  venv_name
 

```
#Reference:
 
-https://github.com/Harsh24893/EmotionRecognition 


#In order to run this download Word2Vec and Glove Vectors, since the file sizes are very large:

[Glove] (https://nlp.stanford.edu/projects/glove/)

[Word2Vec] (https://radimrehurek.com/gensim/models/word2vec.html)              