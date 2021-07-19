## Digit_Recogniser_Kaggle_2


## Approach:
The problem is approached through the usage of keras and CNN. Because each numeric digit has a distinguishing property that distinguishes it from the others, the objective will be to create a model that can extract these characteristics, connect them to the nearest logical digit based on their impact (weight), and then deliver the final result.

## Data Visualization
Visualisation of the dataset helps in better understanding of the data in hand and also helps in developing an intuition on whether a feature would be important in the final prediciton.

## Data preprocessing
Pre-processing data involves removing unwanted attributes from the dataset, filling missing values or removing the tuples with missing values, etc. It overall makes the data useful for the problem or usecase in hand.

1.Dealing with null values

2.Splitting and reshaping data

3.Feature scaling

## Building Model:
The model used here is a sequential one.
Conv2D creates a convolution kernel that is convolved with the layer input to produce a tensor of outputs and also a RELU Activation layer is used.

##Results:

The accuracy is 99.5%
