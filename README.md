# Image-Classification-Using-Deep-Learning
This is a fun little project I made using fastai. The model attempts to predict whether a given image is of Benedict Cumberbatch or not.

The model itself uses transfer learning on ResNet34 (trained on my own database).
The images used for the 'BenedictCumberbatch' class were obtained by using the python urllib to download images from a list of URLs of google images. I used images from the imagenet dataset for the 'not_Benedict' class.
