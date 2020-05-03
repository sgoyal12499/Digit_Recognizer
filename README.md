# Digit Recognizer
This is an implementation of a convolutional neural network for recognizing hand written digits using the MNIST dataset. 
This is an implementation of a convolutional neural network for recognizing hand written digits using the MNIST dataset. This starts with data preparation with reshaping it into tensor of shape(28,28,1) then one basic model which attains a validation accuracy of about 98.32% and then two deep layers models with validation accuracy of 99.35% and 99.39% respectively is obtained after training for 30 and 40 epochs.Later we use Data Augmentation technique to reduce overfitting which increases our validation accuracy. Note that these weights are compatible only with the Tensorflow backend. Note that these weights are compatible only with the Tensorflow backed.

To train the model run `final_model.ipynb` which generates a file `predictions.csv` which contains the predicted labels to the images in the test set. This file can be used for submission at Kaggle. `display_random.py` displays 25 random images from the test set along with their predicted labels. Here is an example:

<img src="https://github.com/Shobhit117/digit-recognizer/blob/master/figure_1.png" height=300px width=400px>

## Requirements

* Python 2.7
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [h5py](http://www.h5py.org/)
* numpy
* matplotlib
* pandas

## Dataset

* The model is trained on the MNIST dataset downloaded from [Kaggle](https://www.kaggle.com/c/digit-recognizer). 

* The file `train.csv` contains pixel intensity values as flattened vectors for 42000 images and their corresponding labels. Similarly, `test.csv` has pixel intensity values for 28000 unlabelled images.




