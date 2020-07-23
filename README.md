# Tensorflow COVID-19 Classification by Chest X-Ray

This is demostration of building Convolutional Neural Network (CNN) model (on top of Densenet) to classify COVID-19 and Normal Chest X-Ray with Tensorflow. After model preparation, export and package it as Tensorflow Serve (TF Serve) compatible format. Model training performance telemetry data will be push to Azure Machine Learning (AML) for tracking and monitoring purpose.

Details article on Medium ([Tensorflow COVID-19 Classification by Chest X-Ray](https://medium.com/@easonlai888/tensorflow-serving-with-azure-cf7626deb906))

* Tensorflow_COVID-19_Classification_by_Chest X-Ray.ipynb > Sample Notebook for local
* Tensorflow_COVID-19_Classification_by_Chest_X-Ray_For_ADB.ipynb > Sample Notebook for Azure Databricks

TensorFlow and Keras version to run code perfectly are 2.1.0 and 2.3.1.

![alt text](https://github.com/easonlai/Tensorflow_COVID-19_Classification_by_Chest_X-Ray/blob/master/git-images/covid19-class.png)

![alt text](https://github.com/easonlai/Tensorflow_COVID-19_Classification_by_Chest_X-Ray/blob/master/git-images/normal-class.png)