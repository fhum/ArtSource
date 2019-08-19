# ArtSource
## Overview
ArtSource is an artificial intelligence project that pursues the classification of art paintings by their art movement. We used several classifying methods to ensure the task, and we found the best approach to be a transfer learning one. We also made use of open source libraries such as Tensorflow and Keras, and wrote our code in Jupyter Notebooks.

## Objectives
### Main Objective
  - Classifying art paintings according to their respective art movement
### Secondary Objectives
  - Testing different approaches in our project with the topics learned in our Artificial Intelligence and Computer Vision courses
  - Trying out state-of-the-art convolutional networks such as ResNet50 and VGG16 in our project, and comparing their results
  - Moving forward in the challenge of computational creativity
  
## Experiments and their results
Our project went through 5 main experiments. Their accuracy results were the following:

  - Gaussian filtering, resize and flattening: 20% on test with Random Forest
  - Bag of words with keypoints: 20% on test with SVM
  - Deep features of ResNet50's fully connected layers: 61% on test
  - Transfer learning and layer freezing with MobileNet: 88% on test
  
  
