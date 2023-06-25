# Homework_week_13

## Overview of the Analysis
The purpose of this analysis is to investigate several deep learning model configurations to attempt to improve the accuracy of its prediction of successful start-ups that Alphabet Soup recieves funding requests from as their vendor capital firm.


## Results

### 1. Original Model has been setup with:
* The same number of inputs as the number of features.
* Two hidden layers.
* *Relu* activation method for the hidden latyers and *Sigmoid* for the output layer.
* The same number of neurons for each layer, as the mean of output layer neurons and number of inputs.

Original Model Results:
```
Epochs = 50
Processing time =  290ms/epoch
Loss =  0.5534992814064026
Accuracy =  0.7300291657447815
``` 

### 2. Alternative Model 1 has been setup with:
* The same number of inputs as the number of features.
* One hidden layer.
* *Relu* activation method for the hidden latyer and *Sigmoid* for the output layer.
* The same number of neurons for each layer, as the same number of inputs.

Alternative Model 1 Results:
```
Epochs = 100
Processing time =  333ms/epoch
Loss =  0.630082368850708
Accuracy =  0.7313119769096375
``` 

### 3. Alternative Model 2 has been setup with:
* The same number of inputs as the number of features.
* One hidden layer.
* *Tanh* activation method for the hidden latyer and *Sigmoid* for the output layer.
* The same number of neurons for each layer, as the mean of output layer neurons and number of inputs.

Alternative Model 2 Results:
```
Epochs = 50
Processing time =  282ms/epoch
Loss =  0.5527206063270569
Accuracy =  0.7301457524299622
``` 

### 4. Alternative Model 3 has been setup with:
* The same number of inputs as the number of features, however the number of features have been reduced in an attempt to remove outliers and new data was trained, tested and split accordingly.
* Two hidden layers.
* *Relu* activation method for the hidden latyers and *Sigmoid* for the output layer.
* The same number of neurons for each layer, as the same number of inputs.

Alternative Model 3 Results:
```
Epochs = 50
Processing time =  369ms/epoch
Loss =  0.709854245185852
Accuracy =  0.709854245185852
``` 