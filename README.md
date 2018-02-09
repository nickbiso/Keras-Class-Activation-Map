# Keras Class Activation Map


This is one of many ways to visualize and get insights from a Convolutional Neural Network. What this basically does is that it creates a heatmap of "Class Activation" over the input image. A "class activation" heatmap is a 2D grid of scores associated with an specific output class, computed for every location in any input image, indicating how important each location is with respect to the class considered. Quite simply, it tells us which features the model is looking for. Keras will be the deep framing framework that is going to be utilized. I am starting to really love Keras, its just so easy to use and as an effect saves a lot of time coding. If tensorflow was used for this project it would have taken longer because tensorflow is not rich in helper functions. Everything that is needed for this are all in Keras.\
\


## Applying MAP to images of the same category


As we expected, the CNN is looking for specific features. In the example below, when it sees this kind of nose/mouth area of a dog the models predicts that it is a greater swiss mountain dog.\
\

![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/output1.jpeg)
![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/output2.jpeg)
![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/output3.jpeg)
![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/output4.jpeg)


## Applying MAP to images of dogs (different breeds)
\

It is interesting what the model is looking for in order to identfy the breed of the dog.\
![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/ahd.jpeg)
![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/bhd.jpeg)
![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/fb.jpeg)
![alt text](https://github.com/nickbiso/Keras-Class-Activation-Map/blob/master/readme_images/maltest.jpeg)
