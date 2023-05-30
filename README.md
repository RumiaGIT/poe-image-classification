# PoE Image Classification

A small project, using a PyTorch-written CNN to navigate an image classification problem, using Path of Exile's fashion sense. 
The CNN used is very basic, and its architecture is based on the TinyVGG architecture. 
The dataset used is a compilation of all items (regular and uniques) in Path of Exile, split up among their ingame base types such as Axes, Flasks, Belts, etc.
For a first iteration, the model's results are adequate, but Path of Exile's catalogue of items contains many unique designs and visuals that may be difficult to predict.

Example:

![PoE Fashion MNIST Example](https://raw.githubusercontent.com/RumiaGIT/poe-fashion-mnist/master/images/example.png 'Example Predictions')



## Contents
~~~
/data:                          Dataset used during the project.
/images:                        Images and examples used in the Jupyter Notebook and readme.
README.md:                      You're reading it.
poe_fashion_mnist.ipynb:        Code for the creation, training, testing, and evaluation of a PyTorch CNN.
~~~
