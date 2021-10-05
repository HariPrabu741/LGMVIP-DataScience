
# MNIST Handwritten Digit Classification

The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems. The MNIST database contains 60,000 training images and 10,000 testing images. Half of the training set and half of the test set were taken from NIST's training dataset, while the other half of the training set and the other half of the test set were taken from NIST's testing dataset. 

## 🛠 Programming language and packages

- Python
- NumPy, Tensorflow, Seaborn, Matplotlib, Scikit-learn.




  
## Steps followed for this project

- Importing packages
- Loading Dataset
- Visualizing image data
- Normalizing the data
- Training and Validating model
- Predicting random data(in test data)

  
## Project Description

- Required packages are imported. From tf.keras.datasets.mnist MNIST dataset is loaded. 
- First five data is visualized with the help of matplotlib. 
- The image value will be between 0 to 255. Normalization is done on it. so that model could learn quickly.
- Sequential model is created with flatten layer and dense layers. Model is compiled.
- Training data and validation data is fitted to the model.
- Random value selected from the test data and used it for prediction.
- And the model is performing pretty good.

