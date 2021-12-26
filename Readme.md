# Food Vision Image Classification using EfficientNet CNN Model through Transfer Learning

In this project, our aim is to construct neural network models (using transfer learning) to perform classification of images into one of the 101 categories as defined in the Food101 dataset.

Our goal is to beat the original Food101 paper's results with only 10% of data.

We're going to perform the following with TensorFlow:

* Downloading and preparing 10% of the Food101 data (10% of training data)
* Training a feature extraction transfer learning model (EfficientNet) on 10% of the Food101 training data
* Fine-tuning our feature extraction model
* Evaluating the performance of our Food Vision model trained on 10% of the training data
* Finding our model's most wrong predictions
* Making predictions with our Food Vision model on custom images of food
