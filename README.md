# Emotion_recognition
It is a basic implementation of emotion recognition using hog(histogram of gradients)

HOG is a powerful algorithm to visualize extracted features in an image using the histogram.

About HOG:
It operates on positive and negative samples where positive samples are images from which our classifier should extract features
From negative samples, the classifier neglects to extract features from images.
HOG has a few parameters such as pixel_per_cell, orientations, and more which must be defined as per our needs.

In the implementation, regularization is also applied.

Finally, extracted features are 1d array with less number of features by applying PCA on a total of 2000 features.

