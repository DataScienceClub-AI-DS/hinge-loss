# Hinge-loss : 

The hinge loss function is used for a binary classification problem, a loss function is used to evaluate how well the given boundary is separating the given data, 
hinge loss is mostly used in SVM, this is used in the combination of the activation function in the last layer. We use Hinge loss to classify whether an email is a spam 
or not.


##Formula = [0, 1- yf(x)]


if yf(x) ≥ 1, hinge loss is ‘0’.



if yf(x) < 1 , hinge loss is increases.

where,

f(x) is  the actual outcome (either 1 or -1),


y is the output of the classifier
