# Is your banana ripe?

## Goal
Funny story, I have been living my life without realizing that I am color deficient in seeing the color green. This creates some problems when navigating the world, specifically getting groceries like fruits. Therefore, this project serves to help people like me, who are color deficient in green, to be able to do specific tasks like identifying whether a banana is ripe or not. 

As a data science major, I'm interested in using this goal to combine with my data science skills to create a deep learning model that could classify whether or not a banana is ripe or not. 

## Tools
• Image processing: cv2, imghdr
  
• Deep learning framework: Tensorflow, Keras

• Machine learning tools: Scikit-learn

• Image visualization: Matplotlib
  

## Result
• Utilized TensorFlow's Keras API to architect a robust 2D Convolutional Neural Network, tailor-made for high-precision ripeness prediction.

• Employed Matplotlib to dynamically visualize the model's training and validation processes, focusing on loss and accuracy metrics, which provided critical insights into model behavior over time.

• Integrated an Early Stopping Callback mechanism, a strategic move to halt the training phase upon detecting an increase in validation loss, thus preventing overfitting and enhancing model reliability.

• Applied Scikit-learn's 5-fold cross-validation technique, a testament to the model's robustness, yielding an impressive accuracy of 95.37% and a loss of 23%, showcasing the model's effectiveness in real-world scenarios.

• Conducted extensive hyperparameter optimization using GridSearchCV, focusing on fine-tuning the L2 regularization rate, learning rate, and dropout rate to discover the most effective configuration for optimal performance.

• Embarked on a comprehensive exploration of various model architectures, ranging in complexity, alongside different numbers of epochs to identify the most efficient model structure for our specific task.

• Compiled the CNN model using the Adam optimizer, a decision aimed at leveraging its adaptive learning rate capabilities to further enhance model performance.

• Evaluated the model's effectiveness using a suite of key metrics, including accuracy, precision, and recall, ensuring a well-rounded assessment of its predictive capabilities.

• Leveraged OpenCV to meticulously download and preprocess over 3,000 images sourced from Google Images, a crucial step in creating a diverse and representative dataset for training and testing our model.

## Limitation
• Because this model has a 95% accuracy level, there's definitely room for improvement in optimizing
the accuracy level and loss level to reach the 100% accuracy and 0% loss level

## Citation
• All of the images used in training this model are taken from Google Images
