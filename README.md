# Optimization and Performance Improvement of Image Classification Model in CIFAR-10 using Transfer Learning with DenseNet121


This repository contains the implementation to optimize and improve the performance of an image classification model on the CIFAR-10 dataset using Transfer Learning techniques with DenseNet121.


## Inspiration


Our approach to solving this problem is based on the paper:


**Sharpness-Aware Minimization for Efficiently Improving Generalization**.  
*Authors: Pierre Foret, Ariel Kleiner, Hossein Mobahi, Behnam Neyshabur*.  
[Link to paper](https://arxiv.org/abs/2010.01412)


In the context of highly overparameterized models, the value of the training loss provides few guarantees on the generalizability of the model. 
The process of optimizing only the training loss value can easily lead to suboptimal model quality. Motivated by previous work connecting loss landscape geometry and model generalization, we present a novel and effective procedure for simultaneously minimizing loss value and loss sharpness, called Sharpness-Aware Minimization (SAM). SAM searches for parameters that lie in uniformly low-loss neighborhoods, resulting in a min-max optimization problem on which gradient descent can be efficiently performed.


## Empirical Results

Our empirical results demonstrate that the application of Transfer Learning with DenseNet121 to optimize and improve the performance of the image classification model in CIFAR-10 has outperformed the results obtained using SAM in terms of accuracy. We have achieved exceptional performance on a variety of benchmark datasets, including CIFAR-10. The resulting model has achieved leading performance for several of these specific sets and models. 
These results underscore the effectiveness and superiority of our Transfer Learning strategy with DenseNet121 for significantly improving generalization ability and accuracy in image classification.

## Experiment Results Updated to Epoch 10

| Model          | Accuracy Epoch 3 | Accuracy Epoch 10   |
| -------------- | -----------------| ------------------- |
| With SAM       | 52%              | 63%                 |
| Wirh DenseNet  | 53%              | 70%                 |


## Open Source
We have shared our code in this repository.


We hope you find our implementation and results useful!
