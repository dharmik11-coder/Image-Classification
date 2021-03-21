# Cifar100-train-test

In this project i have worked with cifar100 dataset in terms of train, validation  and test. This dataset consists of color images of size 32x32 of 100 classes (https://www.cs.toronto.edu/~kriz/cifar.html . Hence, 3 channels R, G, B. I took out 10% for validation (~10000 images) while 50000 images were used in training.

Improved on 44% accuracy (which was a fairly low bar) to achieve an validation accuracy of 62% . Successfuly analysed the  best class accuracy and worst class accuracy of each class. 

To improve, more epochs could help, but the challenge was to  show better performance at 15 epochs while tweaking between different kernel filter sizes, using different optimizers and i executed this task using sequential model and added dense layers and 3 convolution neural network layers to extract as much information as the model could while keeping in mind that the data doesnt overfit oor underfit over a certain trhreshold.

