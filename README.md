# DocuSort
## Summary
This project uses convolution neural networks (CNNs) to "sort" 16 different types/classes of documents. We created our own random subset of 1,250 images from the RVL-CDIP (Ryerson Vision Lab Complex Document Information Processing) dataset, which consists of 400,000 grayscale images with 25,000 images per document class. We used 850 images for training, 210 images for validation, and 200 images for testing. We tested two different CNNs on our classification problem: one simple CNN and one CNN that uses transfer learning. The base model we used for transfer learning was the VGG16 model.

![Screen Shot 2021-04-22 at 12 52 23 PM](https://user-images.githubusercontent.com/47064751/115762936-97497780-a369-11eb-9071-d2007a2a0f05.png)


# Getting Started
## Installing Necessary Programs
1. JupyterLab - In order to open the iPython notebooks used in this project you'll need to install JupyterLab. You can install this from https://jupyter.org/install  
2. Python 3 or higher is necessary to run the iPython notebooks. We reccommend using Python 3.7.6 since that's what we used for this project. Python 3 can be found here https://python.org/downloads

## Download the Dataset
After you download the dataset, add it to the demo folder in your local copy of our GitHub repository. You can download our dataset from [this link](https://drive.google.com/file/d/13OVwU0i3hpzGrzK3XqdxrE6ULTBJliMc/view?usp=sharing)

## Demo
In order to run the project demo, go to the demo folder and click on the Demo.ipynb. This file contains a guided walk-through of the project code and our results.

## Members
1. Dylan Fox
2. Emily Turner
3. Tyler Christian
4. Anthony Ghebranious
5. Munayfah Albaqami

## References
https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb#scrollTo=hLXTofcNYoa2
https://www.cs.mtsu.edu/~jphillips/courses/CSCI4850-5850/private/Open_Lab_6.pdf
