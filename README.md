########################################################################################################
                                                                                                       
                                                                                                       
Download Dataset:- https://drive.google.com/file/d/1cvZdYIVIoBI9Mub3QHI08o1OTqzPQYsu/view?usp=sharing   
                                                                                                       
                                                                                                       
########################################################################################################


# CORONA DETECTION with the help of  CHEST X-Ray Using VGG16(Imagenet) Transfer Learning Convolutional Neural Network Algorithm

World Health Organization has declared Covid-19 as a pandemic. There are a number of test kits available but are either expensive or take time to detect the virus. Deep Learning is State-of-the-art machine learning algorithm and has shown massive development in detecting Covid-19 with the help of chest X-rays.


**Data Used to train Model**

![Screenshot (164)](https://user-images.githubusercontent.com/62375843/183725714-a892f864-b88c-45dc-9f48-e7261c4b06c8.png)            
![Screenshot (165)](https://user-images.githubusercontent.com/62375843/183725749-0fb07700-49a3-42aa-850f-25d61f15f882.png)



**Label Binarization**

![Overview-of-training-a-Neural-Network-for-a-Multi-Label-Classification-task](https://user-images.githubusercontent.com/62375843/183726160-edd74c82-9613-4945-8e26-3d2e52c377e3.png)

![Screenshot (167)](https://user-images.githubusercontent.com/62375843/183726353-2ee1094c-e1b7-4d26-ac3a-508ca2a38c7d.png)

**Convolutional Neural Network**

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. 

![1_vkQ0hXDaQv57sALXAJquxA](https://user-images.githubusercontent.com/62375843/183728148-552e977e-bd3b-42ce-b7e6-72873b73f13e.jpeg)

**VGG16 Transfer Learning Pretrained Convolutional Neural Network**

VGG16 is a type of CNN (Convolutional Neural Network) that is considered to be one of the best computer vision models to date. The creators of this model evaluated the networks and increased the depth using an architecture with very small (3 × 3) convolution filters, which showed a significant improvement on the prior-art configurations. They pushed the depth to 16–19 weight layers making it approx — 138 trainable parameters.

VGG16 is object detection and classification algorithm which is able to classify 1000 images of 1000 different categories with 92.7% accuracy. It is one of the popular algorithms for image classification and is easy to use with transfer learning.
The 16 in VGG16 refers to 16 layers that have weights. In VGG16 there are thirteen convolutional layers, five Max Pooling layers, and three Dense layers which sum up to 21 layers but it has only sixteen weight layers i.e., learnable parameters layer.

VGG16 takes input tensor size as 224, 244 with 3 RGB channel
Most unique thing about VGG16 is that instead of having a large number of hyper-parameters they focused on having convolution layers of 3x3 filter with stride 1 and always used the same padding and maxpool layer of 2x2 filter of stride 2.

![Jjh8f0z](https://user-images.githubusercontent.com/62375843/183730222-7bae0ef5-b17c-4e88-8adc-f868650cf8c7.png)


**Model Prediction**

![Screenshot (169)](https://user-images.githubusercontent.com/62375843/183733804-2fc5f729-a684-41de-9f3b-ef9db74f239a.png)

![Screenshot (171)](https://user-images.githubusercontent.com/62375843/183733826-b8aed336-9617-422f-b3b7-c04a2cfa0cb4.png)








