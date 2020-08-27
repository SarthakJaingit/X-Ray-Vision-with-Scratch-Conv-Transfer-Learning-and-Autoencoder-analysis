# X-Ray Vision with Autoencoders, Transfer Learning, and Convolutional Layers

## Overview
Welcome to the **X-Ray Vision with Autoencoders, Transfer Learning, and Convolutional Layers** Project! In this project, we used a big dataset that contained X-rays for both Pneumonia and Normal chests. With this dataset we did the following objectives:

* Create a Convolutional Neural Network (CNN) from Scatch
* Build an autoencoder from scratch to noisy up then denoise X-ray images
* Visualize the autoencoded output
* Then use transfer learning to classify X-rays
* Create a predicter function that can take a new x-ray and predict whether it is either 
  - Normal X-ray
  - Pneumonia X-ray  
* We then used the predictor for classifying unhealthy X-rays that had cancer or covid
* Finally, we used the predictor to classify the visualized images that were outputs to the Autoencoder.

**Note:** We made two predictors that each used a seperate model to classify

## Getting Started 

You must have anaconda installed. To learn more about installation and managing environment go to the [Documentation](https://anaconda.org/conda-forge/tabula-py)
Also some of the packages that are required for the project:
* numpy
* torchvision
* torch
* matplotlib (inline also)

## Getting Dataset
You can either download the dataset or get access to the entire overview of data through this 
[Kaggle Repository](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/notebooks)

## Clone the Project 
First use `git init`

Then use `git clone https://github.com/SarthakJaingit/X-Ray-Vision-with-Scratch-Conv-Transfer-Learning-and-Autoencoder-analysis.git`

Alertanatives would be to just download the zip file and load it into your own Notebook. 

## Other Options
You can run the code on a GPU which will increase training speeds massively. Project training will be very slow and impractical if used with a CPU.
This project uses CUDA to speed training



