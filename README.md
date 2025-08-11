# Garbage Image Classification
A teamwork project on classifying 10 different categories of garbage images.

## Members
Yutian Mei yt.mei@mail.utoronto.ca
Jiachen Rao jc.rao@mail.utoronto.ca
Jim Yang jima.yang@mail.utoronto.ca

## Motiviation & Description
Sometimes, it is frustrating not knowing which type of garbage you are about to throw out. To address this issue, the team proposes training a deep learning model to classify garbage into three categories, recyclable materials, non-recyclable materials, and organic waste, based on their composition.

The team collected image data from multiple online databases to construct the full dataset for this project. The team explored two methods for building machine learning models to classify the images. The first method was to fine-tune the pre-trained ResNet18 model. The second method was to use a transfer learning technique that utilizes the ResNet18 model to extract features from images, which are then used to train a CNN model to classify the images based on those features. The performences of the models are evaluated and presented.

## Link to datasets:
[https://www.kaggle.com/datasets/alistairking/recyclable-and-household-waste-classification/data] 
[https://www.kaggle.com/datasets/quangtheng/garbage-classification-6-classes-775class?select=plastic]

## References:
[https://pragyanr.medium.com/using-res-net-for-trash-classification-9d25a41d3129]
[https://medium.com/%40d4388707373/garbage-classification-f133c0d2181d]

More details can be found in the .ipynb file.
