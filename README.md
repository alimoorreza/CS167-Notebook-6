# Notebook \#6
Deep learning with MLP and CNN for an image recognition task. 

## The Data: 📊

For this notebook, you will train two deep neural networks: 1) a multilayer perceptron (MLP), and 2) a convolutional neural network (CNN) for an image recognition task (like the cat vs. dog example). In this case, your algorithm will utilize a dataset of images to help learn useful features to classify an image into one of 10 classes. You should be using the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).

The starter notebook contains a snippet of code on how to download the dataset using PyTorch's __torchvision.datasets__ module

## The Exercises: 💪
The assignment is to run an experiment where you try a simple MLP network and a CNN to see which network gives you the best result (in terms of classification accuracy metric). I will be looking for the following:

- In a mark-down cell near the top of your notebook, give a brief explanation of your problem.  
- Build an **MLP** that has this structure (the exact number of parameters is given in the starter notebook as suggestions):
  - One input layer 
  - Three hidden layers
  - One output layer
- Build a **CNN** that has this structure (the exact number of parameters is given in the starter notebook as suggestions):
  - Conv layer 1
  - Conv layer 2
  - Flatten layer
  - Fully Connected layer (Dense)
  - Fully Connected layer (Dense)

- **Train both models** and compare their performance.    
    - You should train each model for enough epochs that your performance on the test set stops improving (i.e., show where you reach overfitting)  OR for at least 1 hour of training time. If you would like to further experiment with additional changes, that is fine, but because these things sometimes take a long time to train.

- **Include graphs** of how well your testing data performed vs. the training data.
- **Conclusions**: Answer the following questions in a markup cell at the bottom of your notebook.
    - How many epochs of training have been utilized for the MLP? How many epochs of training have been utilized for CNN?
    - How accurate can you make your MLP predictor? How accurate can you make your CNN predictor? At which epoch do you anticipate achieving the best results, respectively, for MLP and CNN?
    - What configuration of your DNN (MLP or CNN) proved to be more accurate? Why do you think this is the case?

Use a Markup cell to put your name at the top of the file. Rename your file LastnameNotebook6.ipynb and submit the link to your repository to Blackboard.

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded (out of 1)  | Notes |
| --------- | ------------------- | --------- |
| 1: Problem       |        |                 |
| 2: MLP           |        |                 | 
| 3: CNN           |        |                 |
| 4: Graphs        |        |                 | 
| 5: Conclusions   |        |                 |
| <b>Total         |     /5 | </b>            |
