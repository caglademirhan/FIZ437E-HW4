## FIZ437E-Homework 4
#
### 1) Choose the dataset
Choose a dataset of your interest or you can also create your own image dataset for solving your own image classification problem. We used Python Beautiful Soup package for
web scraping through Google images. 

This dataset contains 4000+ augmented images of book covers, magazine covers and movie posters(PNG) accompanying cover type labels (CSV). There are approximately 1,000 images for each of 3 different cover types grouped into 3 different folders (according to cover type).
#
### 2) Prepare dataset for training
Preparing our dataset for training will involve assigning paths and creating categories (labels), resizing our images.
#
### 3) Create training data
Training is an array that will contain image pixel values and the index at which the image in the CATEGORIES list.
We don’t want our model to over-learn from training data and perform poorly after being deployed in production. So; we need to have a mechanism to assess
how well our model is generalizing. Hence, we separated our input data into training, validation, and testing subsets to prevent our model from overfitting
and to evaluate our model effectively.
#
### 4) Assigning labels and features
Lists will be used in Classification using the NEURAL NETWORKS.
#
### 5) Define, compile and train the CNN model 
Number of epochs and accuracy rates were observed.
Epochs: 75
Batch size: 4
Learning rate: 0.001
#
### 6) Accuracy and score of model
CNN results:
Test loss = 1.435703
Test accuracy of book cover = 28% (50/177)
Test accuracy of magazine cover = 67% (122/180)
Test accuracy of movie poster = 78% (138/175)

Test accuracy overall = 58% (310/532)
#
MLP results:
Test loss = 1.170764
Test accuracy of book cover = 81% (144/177)
Test accuracy of magazine cover = 24% (44/180)
Test accuracy of movie poster = 20% (35/175)

Test accuracy overall = 41% (223/532)



