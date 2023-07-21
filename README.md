# Artwork Image Recognition / https://github.com/World-of-ML/DL-Simplified/issues/356

to predict correct artwork image labels corresponding to their corresponding sign images




Full name : Aditya Narayan Jha

GitHub Profile Link : https://github.com/aditya0929

Email ID : adityajha8906@gmail.com

Participant ID (if applicable): (certificate_id) - 7e43ecd9-76ff-4713-917e-f884b9fedf02

Approach for this Project :
**Image segmentation**

is a crucial task in computer vision that involves identifying and classifying different regions or objects within an image. In this project, I will explore three different approaches for image segmentation using deep learning models:  **Resnet152v2** . **Xception** and **InceptionV3**.

`InceptionV3`

To implement InceptionV3, we start by loading the pre-trained model, which comes with weights learned from the ImageNet dataset. We freeze the layers of the pre-trained model to prevent them from being updated during training, preserving their valuable representations. Next, we add custom layers on top of the pre-trained model, including BatchNormalization, Dense, Dropout, and a final Dense layer with softmax activation for classification. These additional layers enable us to adapt the model to our specific dataset. Finally, we compile the model by specifying an optimizer, a suitable loss function, and metrics for evaluation. This compilation step prepares the model for fine-tuning and training on our dataset.

`ResNet152v2`

i had tried different resnet models for the task but ResNet152v2 seems to have performed the best as it reached an accuracy score of 94% within 10 iterations .  To fine-tune the model for our specific dataset, i had freezed the layers to preserve the learned representations. residual blocks  allows the network to effectively capture multi-scale features and learn intricate representations
