# ML-Food-Classifier
## Dataset
- Taken from [kaggle](https://www.kaggle.com/datasets/dansbecker/food-101/data)
- Sorted 8 categories of that dataset into each category of Soup, Salad and Sandwich
## Training
- Tensorflow, Keras was used to run the machine learning on gpu
- The pretrained EfficientNetV2 model was used
# How to run
## Python
- python 3.10 environment
## Packages
- tensorflow 2.10 (specifically to load our trained model)
- numpy 1.23.5 (to work with tensorflow)
- matplotlib
- scikit-learn
- pillow (for importing images using keras)
### GPU Training
- Cuda 11.2
- cuDNN 8.1
> Follow [this page](https://www.reddit.com/r/deeplearning/comments/1iush30/how_to_successfully_install_tensorflow_with_gpu/) on how to install them in conda 
## Using the Model
> You can either run the full notebook, or skip the training process and load our final model [(fine_tune_at_5.keras)](https://app.box.com/folder/353358119735)