# ERA-S8

# Custom CNN model to classify images of Cifar10 Dataset

Sample images: 

![image](https://github.com/amitdoda1983/ERA-S8/assets/37932202/122eba70-a598-4add-a267-946aaff9da97)


# Model with Group Norm

Using group = 4

### The model network summary :

we have made use of padding to keep the channel size consistent which allows to have the skip connections.There are 2 skip connections in this network.The total number of parameters are 48552

![image](https://github.com/amitdoda1983/ERA-S8/assets/37932202/a4f37903-1503-483c-8b6a-32aa4362f65f)


### Results: 
Train set: Accuracy : 78.36%
Test set:  Accuracy: 7784/10000 (77.84%)

![image](https://github.com/amitdoda1983/ERA-S8/assets/37932202/c599a620-b093-44de-bc02-b3d12cadc006)


### Incorrect predictions samples :

![image](https://github.com/amitdoda1983/ERA-S8/assets/37932202/4fcb8290-bc22-40e5-9220-cdc503bd3bae)


