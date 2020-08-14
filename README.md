# Coursera-Projects
## Detecting COVID-19 with Chest X Ray using PyTorch

Image classification of Chest X Rays in one of three classes: Normal, Viral Pneumonia, COVID-19

Dataset from [COVID-19 Radiography Dataset](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) on Kaggle

The model architecture used is a ResNet-18 from the paper <a href="https://arxiv.org/pdf/1512.03385.pdf">Deep Residual Learning for Image Recognition</a> which is already an inbuilt Neural Network structure in Pytorch. Accuracy achieved is over 96%.

## Bank Customer Segmentation

Unsupervised Machine Learning algorithm for segementing groups of customers into various categories such as Transactors, Revolvers, New Customers, VIP/Premium based on their Credit Card Data with 18 features.

Dataset from [Credit Card Dataset for Clustering](https://www.kaggle.com/arjunbhasin2013/ccdata) on Kaggle

After data pre-processing, Sklearn's inbuilt KMeans model is called to identify similar clusters together and visualized. Next, using the Principal Component Analysis from the inbuilt PCA function, the dimensionality of the dataset is reduced and data is visualized.  
