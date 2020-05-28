# STATS-507-Group-Project
## Fall 2019, UMich
### Thesis
**Plant Seedlings Classification Problem**

This project presents approaches for plant seedlings classification with a dataset that contains 5539 images of plants belonging to 12 different species. The dataset is from Kaggle. We first implement the data processing with background subtraction, data augmentation, normalization and balancing methods. After that, we fit the Convolutional Neural Network (CNN) models as well as two
pretrained models VGG-16 and Resnet-152 to classify the images into 12 classes. By comparing the 4-layer CNN model and the pretrained models, the 4-layer CNN model has better performance. Since there are two species difficult to classify, we utilized the ensemble model and finally achieved a test accuracy of 95.63%.
### Programming softwares and File Description:

Language: Python

Software: Pytorch

The code is shown in [*STATS507_Code_for_final project_Group6.ipynb*] and the Final report see file [*507_Final_Report.pdf*] 
