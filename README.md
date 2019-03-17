# Car Classifier

This is a simple Machine Learning web application allowing to classify 196 different classes of cars.

To run it, simply execute the following command (requires Docker):
```
$ docker-compose up -build
```
 You can then access to the classifier in a browser at the address ***localhost***
 
 # About the application
 
 The application uses the starlette ASGI framework (more information  [here](https://github.com/encode/starlette)).
 
 The Neural Network used for the classification was trained with Pytorch using the resnet34 architecture and the Fastai library for the optimization of the model.
 
 A Jupyter Notebook is provided (see car-classifier.ipynb). It shows how easily the Fastai library handled the processing of the data and the training of the model.
