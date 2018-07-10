# Deep learning tutorials
0)What,where and why of ML
- Learnt about the 5 types of problems that Machine Learning can solve
- Multiple use cases for each problem type
- Difference between AI, ML and DL
 
1)Basic DL terminology 
- What is a perceptron, feedforward neural net (ANN)
- How an ANN learns and came across cost fn, learning rate, gradient descent, activation
- What is overfitting and how to avoid by regularisation and dropout
- Went through the simulation of the learning process of ANN (Tensorflow playground)

2)Implementing a 1 layer network in Tensorflow
  - Covered TF basics (constants, placeholders, variables, session)
  - Trained a Simple linear model in TF (learning the slope and constant)  
  - Built a 1 layer ANN for identifying handwritten digits
  
3)Modifying the 1 layer to DNN and finetuning it
 - Hyper parameter tuning by Adding more layers, random weight initialisation, various activation fns and optimisers 

4)Tackling a real world problem wherein we need to distinguish mines from rocks

5)Improving upon the ANN bulit for mnist by adding convolutional layers
- Why the need of CNNs
- Dimensionality reduction with Convolutional layers, pooling layers in a CNN
- Came across Hyperparmaeters like depth, window size, stride and padding
- Added convolutional layers to fully connected layers and modeled for mnist

6)Using High level framework keras for DL
- Implemented a DNN for mnist in keras
- Tackled a kaagle problem( breast cancer dataset)

7)CNN in keras
- Reimplemented CNN for mnist in keras
- Trained another CNN for fashion dataset

8)Excellent article on how the Conv nets evolved and important developments in computer vision. Check it out
https://adeshpande3.github.io/The-9-Deep-Learning-Papers-You-Need-To-Know-About.html (reading assign :smirk:)

9)Discussed resnet, vgg and other architectures for object identification and implemented them
- Building blocks of vgg,googlenet,resnet and why they work

10)Using pretrained networks to do transfer learning.
- Built a model on cifar10 for the first 5 classes and used it to learn the other 5 classes
- Discussed the advantages of transfer learning
- How the backpropagation works
- Why the need of validation dataset, public and private leaderboards in datascience competitions
- Various activation functions and their associated advantages and disadvantages (vanishing gradient, dead neurons)

11)Data augmentation techniques

12) & 13) Quizzes
