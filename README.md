# rice_classification
Classification of rice grains using CNN.
Our goal is to use convolutional neural networks (cnn) to identify and classify different kinds of rice Arborio, Basmati, Ipsala, Jasmine sticky rice and Long Grain White Rice Karacadag. For each kind of rice, each folder contains 15 000 pictures. The total number of pictures is 75 000. The following analysis is organized as follows. 
Firstly, we import and pre- process the pictures by renaming them. 
Secondly, we create three folders 'test', 'train' and 'valid' with the picture randomly chosen. 
Thirdly, we built a ML model ussing VGG16 to identify the different prices provided in the data set. 
Finally, we train and test the CNN model and visualize the results by plotting the confusion matrix.
