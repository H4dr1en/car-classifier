# Car Classifier

This is a simple Machine Learning web application allowing to classify 196 different classes of cars, with an accuracy of 93%.

To run it, simply execute the following command (requires Docker):
```
$ docker-compose up -build
```

The web app is also running on Amazon Elastic Beanstalk: http://car-classifier.us-east-2.elasticbeanstalk.com/ 

 You can then access to the classifier in a browser at the address ***localhost***. On the web application you can upload the picture of the car you would like to know the class (available classes are shown in the notebook, see last section)
 
 # About the application
 
 The application uses the starlette ASGI framework (more information  [here](https://github.com/encode/starlette)).
 
 The Neural Network used for the classification was trained with Pytorch using the resnet34 architecture and the Fastai library for the optimization of the model.
 
 A Jupyter Notebook is provided (see car-classifier.ipynb). It shows how easily the Fastai library helped handling the processing of the data and the training of the model.
