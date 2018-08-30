# Self-Driving-Car

# Project Description : 

In this project, I use a neural network to clone car driving behavior. It is a supervised regression problem between the car steering angles and the road images in front of a car. Those images were taken from three different camera angles (from the center, the left and the right of the car). As image processing is involved, the model is using convolutional layers for automated feature engineering.

# Training of the Model : 

I used more than 13,000 images of the road to train the self driving car. These images were taken from three different camera angles from the car. I used mean squared error for the loss function to measure how close the model predicts to the given steering angle for each image. I used ModelCheckpoint from Keras to save the model only if the validation loss is improved which is checked for every epoch.

# Result : 

The car successfully steers across the track and predicts correct steering, speed, throttle, reverse, center, left and right values.


