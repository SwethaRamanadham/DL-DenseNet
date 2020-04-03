# DL-DenseNet
DenseNet-BC implementation on CIFAR10


## Team
Anusha Gajinkar - D19008 </br>
Arjun Kumar Singh - D19009 </br>
Swetha R  - D19031 </br>
Sree Soundarya -D19030 </br>
Vasundhara Singh - D19034 </br>

We used CIFAR-10 dataset for our experiments with DenseNet Architecture. 

EDA of the data was done to understand the various class of the image and effect of transformation on the image.

## Hyper Parameters:

Batch Size - 32,48,64,128,256
Epoch - 10,15,20,30,35,40,50,70
Optimizer - RMSprop (with weight decay), SGD (with & without momentum and weight decay)
Transformation - Rotation_Range = 10 , Horizontal Flip , Normalization by mean and Std Dev
Learning Rate - Dynamic learning rate


## Results
	 Accuracy  : 91.09%
