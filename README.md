# Fire Forest Simulator with Neural Network

## 1. The Beginning

![](https://i.ibb.co/d7gQwSm/foto1.png)

From table above,we know that the data consist of 13 columns that contain 12 predictor variables and 1 target variables (area). Area is our target variable that act as numerical data so that we must doing regression method to make a prediction. Beside that, the data doesn't have missing values so we would not consider several techniques, such as cleaning data and imputation. 

## 2. Modelling Neural Network

![](https://i.ibb.co/bg7hrZP/foto-2.png)

We define the model with Artificial Neural Network. A layer as an input predictor variables, two hidden layer with 100 and 50 Layer-Dense respectively, and a layer as an output. We set all the activation function with relu (Rectified Linear Unit) because we want to predict numerical data. We set these parameters arbitrarily. After making this model, we would do hyperparameter tuning so that we could find best parameter that have a good approach to predict data.

## 3. Tuning Epochs

![](https://i.ibb.co/ct0pQn9/foto5.png)

From images above, unfortunately, we could not find any epochs that make godd fitting between train and test, except for 60 epochs. 

![](https://i.ibb.co/W0Zj7mC/foto8.png)

We want to try another approach with higher number of epochs. From images above, we can conclude that 200 epochs and 400 epochs may fit the data. But, it may be not a good approach because too many epochs may cause an overfitting to data. 

![](https://i.ibb.co/fvm8CYY/foto7.png)

We want to try another approach with lower number of epochs. From different number of epochs, we then choose 100 epochs as good approach because it is between overfitting and underfitting, so it may be optimal fit to the data.





