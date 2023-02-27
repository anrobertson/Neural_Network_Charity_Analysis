# Neural_Network_Charity_Analysis

## Overview of Analysis
The objective of this project is to employ deep-learning neural networks utilizing the TensorFlow platform in Python to evaluate and categorize the efficacy of charitable contributions. The analysis incorporates the following approaches:
* Preparing the data for the neural network model through preprocessing.
* Undertaking the tasks of compiling, training, and evaluating the model.
* Engaging in the process of optimizing the model in a professional manner.

## Resources
* [Charity Data CSV](https://raw.githubusercontent.com/anrobertson/Neural_Network_Charity_Analysis/main/AlphabetSoupCharity.csv)
* Python Scikit
* TensorFlow

## Results
### Data Prepocessing
In the course of this project, it was determined that the 'EIN' and name columns were deemed superfluous to the data analysis objectives, and consequently, were excluded from the DataFrame. The IS_SUCCESSFUL column of the dataset is a binary variable that indicates the efficacy of the charity donation. As such, it has been identified as the target variable for our deep learning neural network model. The remaining columns will stay as is for the duration of the project.

### Compiling, Training, Evaluating and Model
After preparing the data, I divided it into training and testing sets and made sure that the features were properly scaled. 

Since the data had about 30 input features, I designed the model's input and first hidden layer with 80 neurons, and added a second hidden layer with 30 neurons. I used ReLU activation for the hidden layers and Sigmoid activation to calculate the output layer's probabilities. The model accuracy was under 75%. This is not a satisfying performance to help predict the outcome of the charity donations. To increase the performance of the model, we applied bucketing and organized the different values by intervals.
## Summary


