This is implementation of Artifical Neural Network from Scratch using simple python(numpy). 

About the implementation: 
  I have implemented separate classes for
  1) Dense Layer
  2) Dropout Layer
  3) Activation functions including ReLU, Softmax, Sigmoid and Linear.
  4) Optimizers including SGD, Adagrad, RMSprop and Adam.
  5) Calculating Loss including regularization loss, categorical - crossentropy, binary - crossentropy, Mean Squared Error and Mean Absolute Error.
  6) Calculating Accuracy for both categorical and regression based models.
  7) Model class which has methods like train, evaluate, predict, forward and backward pass, save and load parameters, save and load entire model.
  
  Both forward and backward methods are introduced in all the classes for prediction and backpropagation.

After implementing the ANN file, I created a model for the fashion_mnist data, and trained the model using all the classes mentioned above. Finally, I saved the model and then, tested it on an out of sample image in a different file after loading the saved model.
