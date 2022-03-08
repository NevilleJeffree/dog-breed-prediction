# dog-breed-prediction
This notebook builds an end-to-end multi-class image classifier usisng TensorFlow 2.0 and TensorFlow Hub.

1. Problem
Identifiying the breed of a dog given an image of a dog.

2. Data
Data source: https://www.kaggle.com/c/dog-breed-identification/data

3. Evaluation
Submissions are evaluated on Multi Class Log Loss between the predicted probability and the observed target.

4. Feature
We are dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
There are 120 dog breeds (this means there are 120 different classes)
There are around 10,000++ images in the training set.
There are around 10,000++ images in the test set.

5. Result
  Score of full model: 0.94900 (Rank 813)
