# SOC-Season-Of-Codes
A repo to contain all the codes for the season of codes for summer of 2022 including final project 


## Files Present

### Pix2Pix_for_Cartoonizing_Images

This is the final implementation of my SoC Project "Cartoonizing Images".
* Used Pix2Pix gan for mapping real images to cartoon images
* used patchgan discriminator
* Dataset used can be found [here](https://www.kaggle.com/datasets/defileroff/comic-faces-paired-synthetic-v2)


### Practice
It contains colab file and other related file and folder which are used for learning about the project and its prerequisites

#### Linear Regression

folder contains a colab file named 'Regression_Model_from_Scratch.ipynb' in which i have written code from scrach for linear regression model.
* This file can easily model multiregression model.
* function + class created contains doc string summarizing arguments taken as input and result generated with expected dimension of these
* used numpy, seaborn and matplotlib for data manipulation and visualization respectively

folder also contains a 'data.csv' file which is used for trainig and testing the model

#### Pytorch Practice

folder contains 'PyTorch_Learning.ipynb' file which is used to learn and implement basic function and methods of Pytorch librray, it contains-
* how to manipulate and create and get the vatrious attributes of Tensors in Pytorch
* various operation on tensors like concatination, view, and algebric operation like dot product, matrix multiplication etc.
* Autograd on Pytorch and how it is used to optain gradient of arbitrary functions
* Build a Dataset class and dataloader to efficiently load dataset for training
* build a neural network classifier of mashrooms type using Pytorch

folder also contains 'mashroom.csv' the dataset used to train classifier


### DCGAN's Implementations

folder contains a colab file 'DCGAN_implementaion_.ipynb' which is used to implement Vanilla DCGAN model to generate Anmie Faces
* The model architecture is similar to that was in the DCGAN'S paper
* Build the Dataset Class and cached the data for faster loading of data , used Anmie Face dataset for model training
* used Binary cross entropy loss function for evaluation losses
* used Adam optimizer

folder also contains 'Dataset_used.txt' which describe where and how to get the datset used


