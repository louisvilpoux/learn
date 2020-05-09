# Practice and Learn :
This repositery is about test, pratice and learn. 

## Notebook `manual_nn_tensorflow.ipynb` :
The goal is to manually create a 1-layer neural network using Tensorflow basic operations (placeholders, matrix multiplication, variables, ...).

Architecture : Input(_,10) -- Dense(4) + Sigmoid -- Dense(1) + Sigmoid

Data : Titanic (from Kaggle).

## Notebook `auto_ml.ipynb` :
The goal is to use the popular package Auto-ML on well known data and better understand what is happening.

Architecture : Input(_,10) -- Not really known (it is magic, tadam !)

Data : Titanic (from Kaggle).

## Notebook `handwritten_reco_dense.ipynb` :
The goal is to perform handwritten digits recognition using Dense layers. This means that the fact of using images as data has not been used (a ConvNet should probably best perform in that case).

Architecture : Input(28,28) -- Dense(300) + Relu -- Dense(100) + Relu -- Dense(10) + Softmax

Data : Mnist dataset

## Notebook `handwritten_reco_cnn.ipynb` :
The goal is to perform handwritten digits recognition using a Convoution Neural Network.

Architecture : Input(28,28) -- Conv(32,3) + MaxPooling -- Conv(64,3) + MaxPooling -- Flatten -- Dense(128) + Relu -- Dense(10) + Softmax

Data : Mnist dataset
