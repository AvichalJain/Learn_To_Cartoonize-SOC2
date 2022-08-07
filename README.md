# Learn To Cartoonize
A repo to contain all the codes for the season of codes for summer of 2022 including final project 


## Files Present

#### Pix2Pix_for_Cartoonizing_Images

This is the final implementation of my SoC Project "Learn To Cartoonize".
* Used Pix2Pix gan for mapping real images to cartoon images
* used patchgan discriminator
* Dataset used can be found [here](https://www.kaggle.com/datasets/defileroff/comic-faces-paired-synthetic-v2)

#### Linear Regression(Gradient Descent)

The code where we implemented linear regression using Gradient Descent
* This file can easily model multiregression model.
* used numpy, seaborn and matplotlib for data manipulation and visualization respectively

#### Pytorch_Learning

This  is used to learn and implement basic function and methods of Pytorch librray, it contains-
* how to manipulate and create and get the vatrious attributes of Tensors in Pytorch
* various operation on tensors like concatination, view, and algebric operation like dot product, matrix multiplication etc.
* Autograd on Pytorch and how it is used to obtain gradient of arbitrary functions
* Build a Dataset class and dataloader to efficiently load dataset for training
* build a neural network classifier of mashrooms type using Pytorch



#### DCGAN's Implementations

This is used to implement Vanilla DCGAN model to generate Anmie Faces
* The model architecture is similar to that was in the DCGAN'S paper
* Built the Dataset Class and cached the data for faster loading of data , used Anmie Face dataset for model training
* used Binary cross entropy loss function for evaluation losses
* used Adam optimizer


