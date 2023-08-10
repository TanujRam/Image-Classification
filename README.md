# Image-Classification
Image Classification - Machine Learning

Image Detection- Unsupervised ML.
Image Classification- Supervised ML

Image size 32pixels

Trained data of over 40000 images of traffic signs using multiple convolutional layers, pooling layers and dense layers.

1.No vehicles
2.Speed limit 30
3.Speed limit 70
4.Roads narrow on right
5.Others ~ 20K images
Dataset Skew 

So different models were trained some models were implemented by undersampling(removing others images)
and some by oversampling(duplicating).

Required features are in the centre so padding doesnt matter much.

Relu activation function to update filters based on I/P images.

Convolution2D layers were added and features were given ranging from 16 to 128

Kernel size: 3 (3*3)

Test data was given to the models and an accuracy of 70-80 was obtained initially, later by the use of adam optimiser we were able to get an accuracy of 99% on test data for a particular model. 
