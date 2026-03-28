# House-price-prediction-model-
A fundamental linear  regression model that is built without using any framework of ML using gradient descent optimizer.

Making models using frameworks to use algorithms in today's time is very easy but I built this very fundamental model to learn in depth about the maths about the working of the algorithms. Exploring the 'blackbox' was the main goal.

PROCESS:

importing pandas and matplotlib for data manipulation and visualisation.

making a function for calculating Mean Absolute Error.

making a function to calculate the gradients of the intercept and slope according to the output and making changes in the final 'm' and 'b' to get the formula of best fit line. The gradient descent optimisation.

Now a function for repetation of the process of revaluating the best fit line.

Finally completed the training process and tested with few random inputs. Haven't used train test split method as well to be sure that I am doing everything manually maximising my learning in linear regression algorithm.


PROBLEMS :

Self generating the dataset was a lengthy part ( using AI to make was one of the choosen paths) as I wanted a very small dataset to begin with.

The major problems were in the python codes. Many times I forgot the basic codes of python then done hit and trial things.

Alast, as my  dataset consists very large no. so taking a learning rate of 0.001 was a bad decision. Figuring out that a learning rate of 10^(-8) was a thing.


My next step will be to build a function for evaluation of the performance of the model like accuracy, F1 score, precision , etc and will figure out which tells the best about the working of model.
