# Chest Disease Detection Using ResNet50

Aim of this project is to detect Covid-19 from X-ray and also to differentiate Covid-19 from viral pneumonia and bacterial pneumonia. I have created a custom dataset that contains covid-19 x-ray images, viral pneumonia x-ray images, bacterial pneumonia x-ray images, and normal person x-ray images. Each class contains 133 images.

The project contains the development of a general chest disease diagnosing system by finetuning Resnet50. The overall obtained test accuracy of the tuned model is 75% for generic disease classification and 100% accuracy for the detection of COVID-19 disease.

ResNet50 is a convolutional neural network architecture that is widely used for various computer vision tasks, such as image classification, object detection, and image segmentation. 

ResNet50 specifically refers to a ResNet model with 50 layers, which includes 48 convolutional layers and 2 fully connected layers. It has a distinctive architecture with residual blocks, each containing several convolutional layers along with skip connections. The skip connections enable the network to learn residual mappings, making it easier to train very deep neural networks effectively.

ResNet50 is pre-trained on a large dataset such as ImageNet, which contains millions of labeled images across thousands of categories. Due to its effectiveness and efficiency, ResNet50 serves as a popular choice as a feature extractor or a starting point for transfer learning in many computer vision applications.


## Dataset

I have used data from https://github.com/ieee8023/covid-chestxray-dataset and https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia. 

0 - Covid-19

1 - Normal X-ray

2 - Viral Pneumonia X-ray

3 - Bacterial Pneumonia X-ray
