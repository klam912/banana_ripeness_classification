# Is your banana ripe?

## Goal
Funny story, I have been living my life without realizing that I am color deficient in seeing the color green. This creates some problems when navigating the world, specifically getting groceries like fruits. Therefore, this project serves to help people like me, who are color deficient in green, to be able to do specific tasks like identifying whether a banana is ripe or not. 

As a data science major, I'm interested in using this goal to combine with my data science skills to create a deep learning model that could classify whether or not a banana is ripe or not. 

## Tools
• Image processing: cv2, imghdr
  
• Deep learning framework: Tensorflow, Keras

• Image visualization: Matplotlib
  

## Result
• Created a 2D Convolutional Neural Network model using Tensorflow's Keras API to predict a banana's ripeness

• Visualized the training and validation loss and accuracy of the model using Matplotlib

• Implemented Early Stopping Callback to stop training the model when the validation loss increases

• Used Scikit-learn's 5-fold cross-validation to test the model's performance, which resulted in 95.37% accuracy and 23% loss

• Hypertuned the model using a GridSearchCV to find the most optimal L2 regularization rate, learning rate, and dropout rate

• Experimented with models with different architecture (from least to most complex) and number of epochs to find the most optimal architecture

• Compiled the CNN model with the Adam compiler

## Limitation
• Because this model has a 95% accuracy level, there's definitely room for improvement in optimizing
the accuracy level and loss level to reach the 100% accuracy and 0% loss level

## Citation
• All of the images used in training this model are taken from Google Images
