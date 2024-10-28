# deep-learning-challenge

## Target Variable:

IS_SUCCESSFUL: This indicates whether an organization was successful (1) or not (0).

## Feature Variables:

APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, INCOME_AMT, ASK_AMT, and other variables relevant to the organization.

## Removed Columns:

EIN and NAME were not included in the training because they did were not meaningful data and would likely skew the model.

## Model Architecture

The first model was built using TensorFlow and Keras libraries. It includes:

1. Input Layer: Based on the number of input features.
2. First hidden layer: 100 neurons, ReLU activation.
3. Second hidden layer: 50 neurons, ReLU activation.
4. Output Layer: 1 neuron with sigmoid activation for binary classification (output 0 or 1).
   
This gave me 9,501 Total parameters.

## Model Training and Performance

The model was trained for 100 epochs.
Overall Accuracy on Training Data was 72.6% but reached 74.6% in the middle epochs.

## Implementated Optimization

1. The classification count remained at 1500<
2. The application count was increased to 1500<
3. Input Layer: Based on the number of input features.
4. First hidden layer: 500 neurons, ReLU activation.
5. Second hidden layer: 250 neurons, ReLU activation.
6. Output Layer: 1 neuron with sigmoid activation for binary classification (output 0 or 1).
   
This gave me 144,501 Total parameters

## Model Training and Performance

The model was trained for 100 epochs
Overall Accuracy on Training Data was 72% but reached 73.5% in the later epochs.
