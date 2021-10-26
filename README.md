# Self-Driving-Car-Image-Segmentation

There are several algorithms that can be used to build Image Segmentation models for self-driving cars or autonomous driving car, such as the UNet architecture, FCN, and others.

For this time, I used the **"UNet architecture"** to model the Image Segmentation, more specifically **"Semantic Segmentation"**. 
I chose the UNet architecture because based on the existing literature on UNet, it is able to increase the accuracy of the model compared to FCN.

There are several algorithms that can be used to build an image segmentation model for self-driving cars, such as the UNet architecture, FCN, and others.
This time, I used the UNet architecture to model image segmentation, specifically Semantic Segmentation. 
I chose the UNet architecture because based on the existing literature on UNet, it is able to improve model accuracy and perform better segments when compared to FCN.

**-- About the Dataset --**

The dataset used for training and testing is using a dataset that has been previously normalized. Thus, the dataset is not preprocessed too deeply, because it has been normalized and ready to be used.
I've also listed the datasets used in the 'Datasets' folder. There are 2 types of data in the dataset: image data, and image results that have been segmented as actual data.

**-- About the Whole Code--**

In general, modeling is carried out through 4 stages, namely Dataset Exploration, Data Preprocessing, Main Code (Build Model, Training, Testing), and Evaluation. 
I've divided each of the four stages into different files, but combined, the evaluation results will remain the same. There are 3 distinct files:
1. Data Exploration
2. Main code (Contains of: Data Preprocessing, Build Model, Training, and Testing)
3. Evaluation
