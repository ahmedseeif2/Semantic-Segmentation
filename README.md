# Semantic-Segmentation:

Semantic Segmentation project on kitti data set as part of ITI AI-Pro internship graduation project.
![alt text](https://nanonets.com/blog/content/images/2020/08/1_wninXztJ90h3ZHtKXCNKFA.jpeg)
Our goal is to build a Semantic segmentation for autonomous vehicles project to locate frontal objects such as roads, dividers, vehicles, pavements, etc. It is a vital subsystem of the vehicle’s navigation system. In order to achieve semantic segmentation in real-time, we have to trade execution speed against achievable segmentation accuracy. Like most successful segmentation networks, our network is structured as an encoder-decoder pair. An encoder CNN detects higher-level objects such as cars or pedestrians in the input image. A decoder takes this information and enriches it with information from the lower layers of the encoder, supplying a prediction for each pixel in the original input. 
We used KITTI Dataset for Semantic segmentation to achieve our goal
The KITTI (Karlsruhe Institute of Technology and Toyota Technological Institute) dataset was released in 2012, but not with semantically segmented images. Other independent groups have annotated frames for their own use cases. Although, there does exist a dataset and benchmark suite for road and lane detection. In this smaller dataset, a variety of sensors including grayscale and color cameras, laser scanners, and GPS/IMU units, are mounted atop a car.


# Refrences:

- [latest papers in segmentation | tracking | detection](https://www.linkedin.com/company/argo-vision)
- [PSPNet implementation](https://medium.com/analytics-vidhya/semantic-segmentation-in-pspnet-with-implementation-in-keras-4843d05fc025)
- [PSPNet explained](https://developers.arcgis.com/python/guide/how-pspnet-works/)
- [Image Segmentation Keras : Implementation of Segnet, FCN, UNet, PSPNet and other models in Keras](https://github.com/divamgupta/image-segmentation-keras)
- [Transfer Learning and Pre-trained ConvNets | Ahmad El Sallab](https://www.youtube.com/watch?v=5Wb6C-d1W-s&list=PLX2D7RnWrLv5f13RK5XvjZ_BMDKBqWriD&index=7)
- [Semantic Segmentation Models](https://paperswithcode.com/methods/category/segmentation-models)
