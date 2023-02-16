# atique597-Research-Assistant-Coding-Task-Two-Computer-Vision
**Image Classification**

The provided image is representing the illusion to the eyes. I provide this image as in inference to 5 different Pre Trained Deep learning models as in input without any weights freezing for the Top Layers. 

I use the PyTorch Framework for the implementations. I map the models predictions outputs with imageNet classes. To evaluate the inference performace of all the models, the results regarding the performance are store in **"Predictions Results"** section.

The Classifier have accurate results by mapping with True imageNet Labels.

1.   **ResNet**
2.   **VGG**
3.  **DenseNet**


Different CNN architecture are better suited to different types of images, and there is possiblity that the these 3 top performing architecture used in ResNet, VGG, and DenseNet is better suited to images that contain the type of visual illusion.


Another reason is the type of networks architecture. They are difference from one another, different numbers of layers in each of the architecture. Trained with differnt weight initilisations, differnt hyperparameters, different optimisers are use in them .


In reality there is always a Tradeoff between speed and accuracy between models 
