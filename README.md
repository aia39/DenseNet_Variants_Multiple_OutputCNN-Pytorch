# Multiple_OutputCNN[Pytorch]
It is training and testing repo for multiple output CNN.Here DenseNet of multiple variants have been implemented.It was created for the competition of 'Bengali.AI Handwritten Grapheme Classification' in Kaggle.

Competition link : https://www.kaggle.com/c/bengaliai-cv19/overview

## Validation score
*DenseNet169 - Validation score:98.349 ,LB score :Timeout error

*Se-ResNext50 - Validation score:99.482 ,LB score :92.64 

*Wide_ResNet50 - Validation score:99.428 ,LB score :93.16  (To download weight file :https://www.kaggle.com/abraristiak39/wideres50 )

All are for grayscale image size of 64*64.These baseline models seem to be overfitting.After selecting best baseline model there is more things to increase performance. 



##Acknowledgement :
Starting code was forked from notebook of :[Hanjoon Choe] https://www.kaggle.com/hanjoonchoe/grapheme-resnet-18-naive-learning-3

