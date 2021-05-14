# Predicting Bike-Sharing Patterns
In this project, you'll get to build a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, you'll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before we move to higher-level tools such as PyTorch. You'll also get to see how to apply these networks to solve real prediction problems!

The data comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset). Also, you can find the data and its specifications [here](https://github.com/Faisal-AlDhuwayhi/Predicting-Bike-Sharing-Patterns/tree/master/Bike-Sharing-Dataset).

## Instructions
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)

You will also need to have Jupyter notebook software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html).

It's recommended to install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 


## Workflow
To complete this project, you need to follow the instructions in the [notebook](https://github.com/Faisal-AlDhuwayhi/Predicting-Bike-Sharing-Patterns/blob/master/Predicting_bike_sharing_data.ipynb); they will lead you through the project. You'll ultimately be editing the [my_answers.py](https://github.com/Faisal-AlDhuwayhi/Predicting-Bike-Sharing-Patterns/blob/master/my_answers.py) python file, whose components are imported into the notebook at various places.


## Conclusios
The model have reached to **Training loss** of 0.065, and **Validation loss** of 0.152.

Finally, using the test data for prediction, it appears that the model reaches a pretty high accuracy. Also, at the first of model predictions, it shows excellent performance of predicting the actual data, or almost perfect. But after that, it seems the model doesn't catch the full correlation and can't predict much well. One potential solution is to feed the model with more data to have a better sense of the correlation and learn more thoughtfully.



