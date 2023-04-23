# 2D_Medical_Image_Segmentation_Workshop
This repository contains an educational notebook that walks the audience through an example 2D medical segmentation project using PyTorch and Monai.
Please open the notebook and proceed through the code (you could also load it in Google Colabatory).

:tv: [**Note: A recorded video session of this workshop is available on YouTube.**](https://youtu.be/8W565F7dMIo) 

We will train a U-Net deep learning model to segment the lungs from chest radiographs. Our output will look like the following:

<img src="https://i.ibb.co/XjKTQ7P/4-png.jpg" alt="4-png" border="0">

### **Important Notes**

#### Dataset

The dataset we will use is the Darwin chest Xray dataset, which contains ~6000 chest X-ray images and their corresponding binary segmentation masks. You can download the Darwin dataset from the following link (no need to do it for this notebook. The dataset will be directly downloaded from the notebook):

https://data.mendeley.com/datasets/8gf9vpkhgy

#### Prerequisites

1- We assume that you have basic knowledge of Python and PyTorch programming. If you are new to PyTorch, you can check out the [PyTorch tutorials](https://pytorch.org/tutorials/). 

2- We assume that you know the basics of deep learning training with PyTorch, e.g., to train a simple image classifier. 

#### Code setup
There are three main differences between how we will write code in this notebook and how we would write code in a real segmentation project:

1- The python code for a real project is usually organized into multiple files, each with a specific purpose. For example, we may have a file for data loading, a file for model definition, a file for training, a file for evaluation, etc. In this notebook, we will write all the code in a single file for simplicity.

2- The code in this notebook is not optimized for performance. For example, we will use a small batch size and a small number of epochs for training. In a real project, we would use a larger batch size and a larger number of epochs to train the model.

3- You will use more functions and classes in a real project. For the sake of simiplicity, we put the majority of the codes in the body of cells in this notebook.
