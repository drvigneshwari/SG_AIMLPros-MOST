# SPAIC | SG_AIMLPros

SPAIC - 2019 Udacity Facebook Secure & Private AI Challenge Scholarship Program  


# Team MOST Project Showcase Challenge

Project <b>MOST</b>, as is suggested by the name, focuses on <b>MO</b>deling and <b>ST</b>atistics.  Its mission is to implement different models on the same dataset and provide statistics regarding the most accurate model for image processing through details collected from the models.

The goal of this project is to classify rice diseases using a rice disease dataset on Kaggle. By using various pretrained models such as VGG19 and ResNet50, we try to determine the best model for this task and analyze the pros and cons of each model, with the end goal of competing in the Udacity Facebook Secure & Private AI Scholarship Project Showcase Challenge.


# Project Overview:

Rice is the staple food for more than half the world's population; accordingly, its supply must double by 2050 to keep up with food demand from population growth. Nearly a fifth of the world’s population are rice farmers. However, they lose approximately 37% of their rice crop yields to various rice diseases. 


<p align="center">
  <img src="https://davidcliveprice.com/wp-content/uploads/2014/11/asian-rice-farmers.jpg" width="350" title="hover text">
  </p>

<p>We came up with a model that classifies whether a rice leaf </p>

1) is healthy:
<br>
<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVdIquvBXmAJo2M1YfCDbJajiaB1BAcOMxJYT0qr82HOsRAIcL" width="150" height="200" title="hover text">
  </p>
</br>

2) has brown spots:
<p align="center">
  <img src="http://www.knowledgebank.irri.org/images/stories/brown-spot-1.jpg" width="150" height="200" title="hover text">
  </p>
  
3) has leaf blast:
<br>
<p align="center">
  <img src="https://miro.medium.com/max/706/1*5OIVPVgxZyPy-OE2Lw8lBg.png" width="150" height="200" title="hover text">
  </p>
</br>

4) or has hispa:
<br>
<p align="center">
  <img src="https://content.peat-cloud.com/hd/rice-hispa--1.jpg" width="150" height="200" title="hover text">
  </p>
</br>

<b><p>We believe that our classification model will help rice farmers better understand the condition of their rice crops and in turn lead to higher yields.
</p></b>


<i><p> For a more detailed project introduction: https://github.com/risper25/MOST- (@risper bevalyn)</p></i>


# Project Participants

 

Following are the Slack handles of the members (total count: 7)

| Name| Slack Name| Github
|--- | ---| --- |
| Vigneshwari Ramakrishnan|@Vigneshwari|https://github.com/drvigneshwari
| Shudipto Trafder |@Shudipto Trafder | https://github.com/Iamsdt 
| Laura Truncellito |@LauraT | https://github.com/ltruncel
| Ellyana Linden |@Ellyana Linden | https://github.com/ellyanalinden
|Risper Bevalyn Adera |@risper bevalyn | https://github.com/risper25
| Shuvam Lal | @happycoder354 |https://github.com/shuvamlal9
| Anna Scott | @Anna Scott |

# Contributions made by the team

## 1) Pre-trained model implementation
1) @Ellyana Linden
2) @Shudipto Trafder
3) @Vigneshwari 
4) @risper bevalyn
5) @happycoder354

## 2) Technical documentation | Other
|Slack Name|Contribution Areas|
|---| ---|
| @LauraT |Description of the models, Readme file |
| @Vigneshwari |Readme file, project deck, Github Project repo, portfolio |
| @risper bevalyn| Introduction of the project, data collection and chart in google sheet |
| @Shudipto Trafder| Essential attributes identification and listing, Readme file |
   
# Dataset utilized

Datasets: [Rice Diseases Image Dataset](https://www.kaggle.com/minhhuy2810/rice-diseases-image-dataset)

## Details of the dataset

Dataset of rice images -  4 labels/categories (3 diseases and pests, 1 healthy) 
1) Brown spots (523 files)
2) Healthy (1488 files)
3) Hispa (565 files)
4) Leaf blast (779 files)

# Pretrained models used in this project

1) GoogleNet
2) ResNet50
3) VGG19
4) Resnext101_32x8d
5) Densenet201
6) Alexnet

## Link to our project deck / activity records

Link: https://github.com/drvigneshwari/SG_AIMLPros-MOST/projects/1

## Links to all models implemented by the participants 

| Slack Name| Model Name | Kernel Link |
| --- | ---| ---|
| @Ellyana Linden | GoogleNet | [googlenet.ipynb](https://github.com/ellyanalinden/rice_diseases_kaggle/blob/master/googlenet.ipynb)
| @Ellyana Linden | Resnet50 | [googlenet](https://www.kaggle.com/ellyanalinden/googlenet)
| @Shudipto Trafder | resnext101_32x8d | [kernelcd66c7e01d-version1](https://www.kaggle.com/iamsdt/kernelcd66c7e01d?scriptVersionId=17795486)
| @Shudipto Trafder | resnet 50 | [kernelcd66c7e01d](https://www.kaggle.com/iamsdt/kernelcd66c7e01d)
| @Vigneshwari | Alexnet | [kernel4946364e36](https://www.kaggle.com/drvigneshwari/kernel4946364e36)
| @risper bevalyn, @happycoder354 | VGG19 | [rice-leaves-disease-classifier](https://www.kaggle.com/risperbevalyn/rice-leaves-disease-classifier?scriptVersionId=17832475)

# Implemented model chart and details

# Analysis

### Test accuracy:
GoogleNet results had the highest accuracy (97%), followed by ResNext101_32x8 (81%), ResNet50 (79%, 10 epochs), ResNet50 (69%, 25 epochs), Alexnet (66%), and VGG19 (61%)

### Optimizers:
Two optimizers were selected: Adaptive Moment Estimation (Adam) and Stochastic Gradient Descent (SGD).  Adam is used by @Shudipto Trafder for training resnet 50, and the remaining models were all trained with SGD as an optimizer.

### Loss function:
Cross-entropy loss, or log loss, is used to measure the performance of all classification models in this project.

### Learning rate:
The learning rates of pretrained models selected in this project range between 0.001 and 0.003.  


<p>For details of the test accuracy and epochs:</p>
<p>https://docs.google.com/spreadsheets/d/1ZMs9j4nvNw2387g6x5ZdN9uEodQqYqnViGnDU-fwNxQ/edit#gid=0</p>


# Conclusion

GoogleNet is a class of architecture designed by researchers at Google. It was the winner of ImageNet 2014, and it was proven in our project to be a winner as well.  




# Resources used for reference
@Ellyana Linden - DLND Udacity course

https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

https://pytorch.org/docs/stable/torchvision/models.html

@Vigneshwari

https://www.learnopencv.com/pytorch-for-beginners-image-classification-using-pre-trained-models/

https://pytorch.org/docs/stable/torchvision/models.html

@LauraT

<p>CNN Architectures: LeNet, AlexNet, VGG, GoogLeNet, ResNet and more</p> 
<p>(https://medium.com/@sidereal/cnns-architectures-lenet-alexnet-vgg-googlenet-resnet-and-more-666091488df5)</p>

<p>Going Deeper with Convolutions</p>
<p>https://www.cs.unc.edu/~wliu/papers/GoogLeNet.pdf</p>

10 Advanced Deep Learning Architectures Data Scientists Should Know
https://www.analyticsvidhya.com/blog/2017/08/10-advanced-deep-learning-architectures-data-scientists/

<p>TORCHVISION.MODELS</p>
<p>https://pytorch.org/docs/stable/torchvision/models.html</p>




