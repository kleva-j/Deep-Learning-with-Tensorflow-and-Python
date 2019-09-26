## Exercise 1

### Instructions

In this exercise we'll build a neural network that predicts the price of a house according to a simple formula.

So, imagine if house pricing was as easy as a house costs 50k + 50k per bedroom, so that a 1 bedroom house costs 100k, a 2 bedroom house costs 150k etc.

How would you create a neural network that learns this relationship so that it would predict a 7 bedroom house as costing close to 400k etc.

Hint: Your network might work better if you scale the house price down. You don't have to give the answer 400...it might be better to create something that predicts the number 4, and then your answer is in the 'hundreds of thousands' etc.

## Exercise 2

### Instructions

In the course we'll implement classification using Fashion MNIST, a data set containing items of clothing. There's another, similar dataset called MNIST which has items of handwriting -- the digits 0 through 9.

Write an MNIST classifier that trains to 99% accuracy or above, and does it without a fixed number of epochs -- i.e. you should stop training once you reach that level of accuracy.

Some notes:

* It should succeed in less than 10 epochs, so it is okay to change epochs= to 10, but nothing larger
* When it reaches 99% or greater it should print out the string "Reached 99% accuracy so cancelling training!"
* If you add any additional variables, make sure you use the same names as the ones used in the class
