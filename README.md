# Self-Driving-Car

# Project Description : 

In this project, I used a neural network to clone car driving behavior. It is a supervised regression problem between the car steering angles and the road images in front of a car. Those images were taken from three different camera angles (from the center, the left and the right of the car). As image processing is involved, the model is using convolutional layers for automated feature engineering.

# Training of the Model : 

I used more than 13,000 images of the road to train the self driving car. These images were taken from three different camera angles from the car. I used mean squared error for the loss function to measure how close the model predicts to the given steering angle for each image. I used ModelCheckpoint from Keras to save the model only if the validation loss is improved which is checked for every epoch.

# Screenshots :

![screenshot-1](https://user-images.githubusercontent.com/34116562/45925117-26c9e800-bf2d-11e8-8fb0-63fb18a1e3c2.png)
![screenshot from 2018-09-09 11-52-26](https://user-images.githubusercontent.com/34116562/45925120-45c87a00-bf2d-11e8-82e6-21b7d53f14ae.png)
![screenshot from 2018-09-09 11-52-40](https://user-images.githubusercontent.com/34116562/45925121-48c36a80-bf2d-11e8-9940-40dcfb8dd025.png)
![screenshot from 2018-09-09 11-52-45](https://user-images.githubusercontent.com/34116562/45925123-4d881e80-bf2d-11e8-9ddc-9a29324ea74f.png)
![screenshot from 2018-09-09 11-53-08](https://user-images.githubusercontent.com/34116562/45925125-537dff80-bf2d-11e8-910e-69c4a76d2328.png)
![screenshot from 2018-09-09 11-53-12](https://user-images.githubusercontent.com/34116562/45925126-5ed12b00-bf2d-11e8-8fc8-c1ba1569bcb5.png)
![screenshot from 2018-09-09 11-53-27](https://user-images.githubusercontent.com/34116562/45925127-6264b200-bf2d-11e8-9c7e-0980f9a56ed0.png)
![screenshot from 2018-09-09 11-53-40](https://user-images.githubusercontent.com/34116562/45925128-655fa280-bf2d-11e8-862a-0e03823b990a.png)
![screenshot from 2018-09-09 11-53-55](https://user-images.githubusercontent.com/34116562/45925130-698bc000-bf2d-11e8-8329-6dfaa6c39eb5.png)
![screenshot from 2018-09-09 11-54-09](https://user-images.githubusercontent.com/34116562/45925137-6c86b080-bf2d-11e8-9d19-7bc7587ac487.png)
![screenshot from 2018-09-09 11-54-18](https://user-images.githubusercontent.com/34116562/45925140-701a3780-bf2d-11e8-8e0d-ff3514da1c1e.png)


# Result : 

The car successfully steers across the track and predicts correct steering, speed, throttle, reverse, center, left and right values.


