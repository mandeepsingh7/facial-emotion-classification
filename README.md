# Facial Emotion Recognition

- In this project, we implement PCA (Principal Component Analysis), LDA (Linear Discriminant Analysis) and Neural Network from scratch.
- Dataset contains 2 folders, train and test.
- Train folder contains 20 images. 10 images are of a sad person and 10 images are of a happy person.
- Test folder contains 10 images. 5 images are of a sad person and 5 images are of a happy person.
- Each image is of dimension (101, 101). 
- When we unroll an image, we get a feature size of 10201 which is really big incomparison to number of samples (20).
- So we reduce the number of features from 10201 to a number less than 20 using Principal Component Analysis.
- Then we use Linear Discriminant Analysis to see what is the appropriate number of components we need to consider to get maximum class separability.
- Then we use Neural Network for classification of images into sad and happy emotion.