# Simple-Linear-Regression-in-Python

You will learn about the generic steps that are required to build a simple linear regression model. You will first read and visualise the dataset. Next, you will split the dataset into train and test sets. After that, you will build the model on the training data and draw inferences. We have used the dataset and example from the ISLR book. You will use the advertising dataset given in ISLR and analyse the relationship between 'TV advertising' and 'sales' using a simple linear regression model. You will learn to make a linear model using two different libraries: statsmodels and SKLearn.

Before moving on to the Python code, we need to address an important aspect of linear regression: the assumptions of linear regression.
While building a linear model, you assume that the target variable and the input variables are linearly dependent.

Before moving on to the Python code, we need to address an important aspect of linear regression: the assumptions of linear regression.

>There is no problem if the error terms are not normally distributed if you just wish to fit a line and not make any further interpretations.
>But if you are willing to make some inferences on the model that you have built (you will see this in the coming segments), you need to have a notion of the distribution of the error terms. One particular repercussion of the error terms not being normally distributed is that the p-values obtained during the hypothesis test to determine the significance of the coefficients become unreliable. (You'll see this in a later segment)
>The assumption of normality is made, as it has been observed that the error terms generally follow a normal distribution with mean equal to zero in most cases.


While building a linear model, you assume that the target variable and the input variables are linearly dependent.
