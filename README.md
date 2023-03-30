# A Comparison of Optimizer
## 1.Introduction
With the development of society and the advancement of science and technology, artificial intelligence has gradually emerged, and machine learning has also been applied to more and more fields. Deep learning is a hot research direction for machine learning. It is currently widely used in the fields of picture recognition, natural language processing, robotics and control. In deep learning algorithms, the model structure and optimization method are two main factors that affect the performance of the model. In particular, optimization directly affects the speed and performance of deep learning algorithms, so it is necessary to study the optimization of deep learning algorithms[1]. This project mainly does research on the algorithms and performance of different optimizers in different deep learning tasks.
## 2.Steps of reproduce the experiments
### 2.1 Download the datasets
Download the required datasets from keras.datasets module and import them.
### 2.2 Data preprocess
Transform the data types and labels.
### 2.3 Construct the models
Construct models by constructing different layers of convolutional neural networks(CNNs).
### 2.3 Compile
Replace different optimizers using the model.compile() statement.
### 2.4 Train the model
Use model.fit() to train the training datasets and check different results of four optimizers.
### 2.5 Test the model
Use model.evaluate() to predict the testing datasets.
## 3.Visualization
Calculate the loss function and accuracy of each model, and use matplotlib.pyplot module to show the loss function and accuracy of different optimizers of each epoch.
