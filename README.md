#   TASK4
## Create a project using transfer learning solving various problems like Face Recognition, Image Classification, using existing Deep Learning models like VGG16, VGG19, ResNet, etc.
#### Objectives
A. **Transfer Learning** --> In deep learning, transfer learning is a technique whereby a neural network model is first trained on a problem similar to the problem that is being solved. One or more layers from the trained model are then used in a new model trained on the problem of interest.

B. **VGG16** --> VGG16 is a convolutional neural network model which achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes.

**Steps used to to do work:**
Step 1: Creation of tensorflow environment in anaconda
`conda create --name tf_new python=3.7 tensorflow jupyter`
and activate the enviornment `activate tf_new`.

The packages like opencv and numpy are also installed using `conda install opencv-contrib-python` and jupyter notebook is launched.

Step 2: Dataset is created firstly under train folder where my images and Johhny Depp images is taken from google. The github repository is created and files are pushed into it.
Train Data: 
![Train data](/transferlearning/data/train/rahul/)
and Test data:
![Test data](/transferlearning/data/test/jdepp/)
are created.
Step 3:  Transferlearning-VGG16.ipynb is executed.


1. It shows the importing of different packages.

![](/transferlearning/Screenshot%20(223).png) 

2. The train data is trained and classes is found out.Later the dataset is loaded.

![](/transferlearning/Screenshot%20(225).png)

3.The accuracy is found out with help of VGG16 model.

![](/transferlearning/Screenshot%20(224).png)

Step 4: Model is saved using .h5 extension

![](/transferlearning/Screenshot%20(226).png)

Step 5: The saved model is validated using the test data and accuracy is found out in comaparison of both person

![](/transferlearning/Screenshot%20(227).png)


Conclusion: We can use different models like MobileNet, Resnet,VGG19, Inception v3 for training and testing data.

















