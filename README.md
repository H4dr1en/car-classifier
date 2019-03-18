# Car Classifier

This is a simple Machine Learning web application allowing to classify 196 different classes of cars, with an accuracy of 93%.

The web app is running on Amazon Elastic Beanstalk: http://car-classifier.us-east-2.elasticbeanstalk.com/ 

To run it locally, simply execute the following command (requires Docker):
```
$ docker-compose up -build
```
You can then access to the classifier in a browser at the address ***localhost***. On the web application you can upload the picture of the car you would like to know the class (available classes are listed [here](https://github.com/H4dr1en/car-classifier/blob/master/app/cars_meta.txt))
 
 # About the application
 
 The application uses the starlette ASGI framework (more information  [here](https://github.com/encode/starlette)).
 
 The Neural Network used for the classification was trained with Pytorch using the resnet34 architecture and the Fastai library for the optimization of the model.
 
 A Jupyter Notebook is provided (see [car-classifier.ipynb](https://github.com/H4dr1en/car-classifier/blob/master/car-classifier-training.ipynb)). It shows how easily the Fastai library helped handling the processing of the data and the training of the model.
