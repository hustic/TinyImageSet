# ACSE 4.4 - Machine Learning Miniproject

## The Identification Game
### The Data
This project is an image classification problem consisting of Natural Images. You are provided a dataset consisting of images and associated labels. Most of the images have 3 channels for colour, RGB, meaning they are 64x64x3 arrays. Each image belongs to exactly one out of 200 categories. The dataset contains 100k images (500 from each category). You will also have a second dataset - the test set. You will not have the labels for these. Any further validation/test splits are your responsibility.

<center class="half">
    <img src="https://github.com/acse-2019/acse4-4-logistic/blob/master/train_images_preview/n01443537_10.JPEG" width="100"/><img src="https://github.com/acse-2019/acse4-4-logistic/blob/master/train_images_preview/n02791270_2.JPEG" width="100"/><img src="https://github.com/acse-2019/acse4-4-logistic/blob/master/train_images_preview/n02814533_2.JPEG" width="100"/><img src="https://github.com/acse-2019/acse4-4-logistic/blob/master/train_images_preview/n09193705_7.JPEG" width="100"/>
</center>

### The Task
Train a classifier that can take as input an image that is similar to the ones provided in the dataset, and output a class corresponding to this image.

All information available here: https://www.kaggle.com/c/acse-miniproject/overview.

## User guide
We implemented multiple models to classify 100 000 images into 200 classes (500 in each class). To train the models, simply run the Jupyter notebook [identification_game.ipynb](identification_game.ipynb).

## Additional information
The presentation slide for the project can be found here [acse4-4-logistic.pptx](acse4-4-logistic.pptx).
