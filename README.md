# Random-Walker-segmentation
Random Walker segmentation in Python using a noisy backscattered electron (BSE) image collected from an alloy


The notebook includes implementation of Random Walkder Segmentation method for performing multilabel image segmentation. Given a small number of pixels with user-defined (or pre-defined) labels, one can analytically and quickly determine the probability that a random walker starting at each unlabeled pixel will first reach one of
the pre-labeled pixels. By assigning each pixel to the label for which the greatest probability is calculated, a high-quality image segmentation may be obtained


Further Details at 
https://scikit-image.org/docs/dev/api/skimage.segmentation.html#skimage.segmentation.random_walker

## Orignal Image 

![Image of Yaktocat](https://github.com/alam121/Random-Walker-segmentation/blob/master/Orignal%20Image.JPG)

## Segmented Result
![Image of Yaktocat](https://github.com/alam121/Random-Walker-segmentation/blob/master/Segmented-Result.png)

