# DLND Face Generation

## Introduction

In this project, we'll use generative adversarial networks (GAN) to generate new images of faces.

We'll be using two datasets in this project:
 - MNIST
 - CelebA

Since the celebA dataset is complex, we'll develop, test and tune our GAN against MNIST before CelebA.

![alt text](https://www.smashinglists.com/wp-content/uploads/2010/03/kate-winslet-scarlet-johanson-600x251.jpg "Logo Title Text 1")
![alt text](https://www.smashinglists.com/wp-content/uploads/2010/03/John-Travolta-and-Johnny-Depp-600x249.jpg "Logo Title Text 1")

## Prerequisite (OSX/Linux)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Anaconda 3](https://www.continuum.io/)
* [Tensorflow](https://www.tensorflow.org/)

## Instruction

    conda create -n tensorflow-1.1-gpu python=3.5
    source activate tensorflow-1.1-gpu
    conda install pandas matplotlib jupyter notebook scipy scikit-learn pillow tqdm
    pip install tensorflow-gpu==1.1
