# Week 2

## Binary Classification

*Example: Suppose we have a set of images and want to build a classifier to predict whether an image is of a cat (1) or not-cat (0).*

- Images are represented as sets of pixel intensity values (rows by columns) for different color channels. 
Suppose each input image is 64x64 and they are color images, then each image has dimension 64x64x3 since there are red, green, and blue color channels. 

- If we choose to build a simple binary classifier with logistic regression, then we actually have to take these input matrices and unravel them into long feature vectors since logistic regression takes vectors as inputs, not matrices. Then, each of our input vectors has dimension, `n_{x}` or `n`, 12288. A big advantage of CNNs is that they can take in matrices as inputs!

