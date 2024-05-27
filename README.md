# Facial Emotion Classification

- In this project, we implement PCA (Principal Component Analysis), LDA (Linear Discriminant Analysis) and Neural Network from scratch.
### Dataset:
  - `notebook/data/train/`: Contains 20 images (10 sad and 10 happy).
  - `notebook/data/test/`: Contains 10 images (5 sad and 5 happy).
### Image Dimensions:
  - Each image is of size (101, 101), resulting in 10201 features when unrolled.
    
- When we unroll an image, we get a feature size of 10201 which is really big in comparison to the number of samples (20).
- So we reduce the number of features from 10201 to a number k less than 20 using Principal Component Analysis.
- Then we use Linear Discriminant Analysis to find out the appropriate number of components we need to consider to get maximum class separability.
- Then we use Neural Network for the classification of image into sad and happy emotion.
