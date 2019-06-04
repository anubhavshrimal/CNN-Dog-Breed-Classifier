[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This project is done as a part of the Udacity's [Deep Learning Nanodegree](https://eu.udacity.com/course/deep-learning-nanodegree--nd101). Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

Convolutional Neural Networks are implemented using PyTorch framework and Transfer Learning is also performed for better accuracy using pretrained VGG16.

Sample output of the project:

![Sample Output][image1]


## Objectives

Along with exploring state-of-the-art CNN models for classification and localization, the project will allow you to make important design decisions about the user experience for the app. The goal is to understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.


## Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/anubhavshrimal/CNN-Dog-Breed-Classifier.git
		cd CNN-Dog-Breed-Classifier/
	```
2. Install required dependencies using:
```
		pip install -r requirements.txt
```
3. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
4. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
5. Open a terminal window and navigate to the project folder. Open the notebook using the bellow command and follow the instructions given in the notebook.
	
	```
		jupyter notebook dog_app.ipynb
	```


## (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you can use [Google Colab](https://colab.research.google.com/). 

**Note:** Colab is a free service and the data is not persistent. It is suggested to download whatever data you need once your session is idle otherwise you may lose the progress.

You can use Amazon Web Services to launch an EC2 GPU instance which will be persistent. (This costs money)
