# dog_cat_classification_kaggle

### Overview
There are 12500 cat images and 12500 dog images (total 25000) for training, whereas 12500 images for testing. Download the dataset from [here](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition). The aim is to classify the cat image and dog image. Here, dog represent "1" label and cat represent "0" label.

### Dependencies
- Python (>3.6)
- keras

### Approach
- I have used vgg19 model with "imagenet" weights to evaluate this task. The training took  around 8 hours to train the model with 94.7% accuracy.

- For testing 12500 images, it took 3 hours to predict the labels.


